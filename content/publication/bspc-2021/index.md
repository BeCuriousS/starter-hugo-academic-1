---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Optimal color channel combination across skin tones for remote heart rate measurement in camera-based photoplethysmography"
authors: ["Hannes Ernst", "admin", "Hagen Malberg", "Martin Schmidt"]
date: 2021-07-01T00:00:00
doi: "10.1016/j.bspc.2021.102644"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "**Objective**: The heart rate is an essential vital sign that can be measured remotely with camera-based photoplethysmography (cbPPG). Systems for cbPPG typically use cameras that deliver red, green, and blue (RGB) channels. The combination of these channels has been proven to increase signal-to-noise ratio (SNR) and heart rate measurement accuracy (ACC). However, many combinations remain untested, the comparison of proposed combinations on large datasets is insufficiently investigated, and the interplay with skin tone is rarely addressed.


**Methods**: Eight regions of interest and eight color spaces with a total of 25 color channels were compared in terms of ACC and SNR based on the Binghamton-Pittsburgh-RPI Multimodal Spontaneous Emotion Database (BP4D+). Additionally, two systematic grid searches were performed to evaluate ACC in the space of linear combinations of the RGB channels.


**Results**:Glabella and forehead regions of interest provided highest ACC (up to 74.1 %) and SNR (> -3 dB) with the hue channel H from HSV color space and the chrominance channel Q from NTSC color space. The grid searches revealed a global optimum of linear RGB combinations (ACC: 79.2 %). This optimum occurred for all skin tones, although ACC dropped for darker skin tones.


**Conclusion**: Through systematic grid searches we were able to identify the skin tone independent optimal linear RGB color combination for measuring heart rate with cbPPG. Our results proved on a large dataset that the identified optimum outperformed conventionally used color channels.


**Significance**: The presented findings provide useful evidence for future considerations of algorithmic approaches for cbPPG."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Algorithmic"]
categories: []
featured: false

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
  focal_point: "Smart"
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
