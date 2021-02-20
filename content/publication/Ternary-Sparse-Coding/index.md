---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Ternary Sparse Coding"
authors: ["Georgios Exarchakis", "Marc Henniges", "Julian Eggert", "Jörg Lücke"]
date: 2012-06-18T18:29:37+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2012-06-18T18:29:37+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "International Conference on Latent Variable Analysis and Signal Separation"
publication_short: "LVA/ICA"

abstract: "We study a novel sparse coding model with discrete and symmetric prior distribution. Instead of using continuous latent variables distributed according to heavy tail distributions, the latent variables of our approach are discrete. In contrast to approaches using binary latents, we use latents with three states (-1, 0, and 1) following a symmetric and zero-mean distribution. While using discrete latents, the model thus maintains important properties of standard sparse coding models and of its recent variants. To efficiently train the parameters of our probabilistic generative model, we apply a truncated variational EM approach (Expectation Truncation). The resulting learning algorithm infers all model parameters including the variance of data noise and data sparsity. In numerical experiments on artificial data, we show that the algorithm efficiently recovers the generating parameters, and we find that the applied variational approach helps in avoiding local optima. Using experiments on natural image patches, we demonstrate large-scale applicability of the approach and study the obtained Gabor-like basis functions."

# Summary. An optional shortened abstract.
summary: ""

tags: ["unsupervised learning", "sparse coding", "natural image statistics"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://link.springer.com/content/pdf/10.1007%2F978-3-642-28551-6.pdf
url_code: https://github.com/ml-uol/prosper
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
