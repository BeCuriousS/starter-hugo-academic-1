---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Predicting sepsis with a recurrent neural network using the MIMIC III
database"
authors: ["admin", "Felix Gräßer", "Hagen Malberg", "Sebastian Zaunseder"]
date: 2019-08-01T00:00:00
doi: "10.1016/j.compbiomed.2019.103395"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: "Sepsis prediction from clinical data"

abstract: "**Objective**: Predicting sepsis onset with a recurrent neural network and performance comparison with InSight - a previously proposed algorithm for the prediction of sepsis onset.


**Methodology**: A retrospective analysis of adult patients admitted to the intensive care unit (from the MIMIC III database) who did not fall under the definition of sepsis at the time of admission. The area under the receiver operating characteristic (AUROC) measures the performance of the prediction task. We examine the sequence length given to the machine learning algorithms for different points in time before sepsis onset concerning the prediction performance. Additionally, the impact of sepsis onset's definition is investigated. We evaluate the model with a relatively large and thus more representative patient population compared to related works in the field.


**Results**: For a prediction 3 h prior to sepsis onset, our network achieves an AUROC of 0.81 (95% CI: 0.78–0.84). The InSight algorithm achieves an AUROC of 0.72 (95% CI: 0.69–0.75). For a fixed sensitivity of 90% our network reaches a specificity of 47.0% (95% CI: 43.1%–50.8%) compared to 31.1% (95% CI: 24.8%–37.5%) for InSight. In addition, we compare the performance for 6 and 12 h prediction time for both approaches.


**Conclusion**: Our findings demonstrate that a recurrent neural network is superior to InSight considering the prediction performance. Most probably, the improvement results from the network's ability of revealing time dependencies. We show that the length of the look back has a significant impact on the performance of the classifier. We also demonstrate that for the correct detection of sepsis onset for a retrospective analysis, further research is necessary."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Deep Learning", "Machine Learning"]
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
projects: ["sepsis-prediction"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
