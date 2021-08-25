---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "DeepPerfusion: Camera-based Blood Volume Pulse Extraction Using a 3D
Convolutional Neural Network"
authors: ["admin", "Hannes Ernst", "Hagen Malberg", "Martin Schmidt"]
date: 2020-12-01T00:00:00
doi: "10.22489/CinC.2020.388"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Imaging photoplethysmography (iPPG) is a camerabased approach for the remote extraction of the blood volume pulse (BVP) most commonly applied to facial video recordings. The major challenges of this promising technique are the low amplitude of BVP signals and their superposition with artifacts as well as physiological and non-physiological movement induced distortions. We addressed this complexity with a 3D convolutional neural network, which we called DeepPerfusion, to improve BVP extraction from iPPG. Our approach is based on the idea of enabling DeepPerfusion to learn the extraction of the BVP from videos by understanding their relation to the ground truth signals. First results show that DeepPerfusion outperforms state-of-the-art algorithms for remote BVP extraction demonstrating a mean absolute error of 0.66 beats per minute (up to 60% improvement) regarding the BVP based pulse rate estimation for 21 randomly chosen held out test subjects of the UBFC dataset."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Deep Learning", "Machine Learning"]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
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
  focal_point: "Top"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ["imaging-photoplethysmography"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
