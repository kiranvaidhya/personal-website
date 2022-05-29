---
title: 'Deep Learning for Malignancy Risk Estimation of Pulmonary Nodules Detected at Low-Dose Screening CT'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Arnaud Arindra Adiyoso Setio
  - Anton Schreuder
  - Ernst Scholten
  - Kaman Chung
  - Mathilde Marie Winkler Wille
  - Zaigham Saghir
  - Bram van Ginneken
  - Mathias Prokop
  - Colin Jacobs

date: '2021-07-27T00:00:00Z'
doi: '10.1148/radiol.2021204433'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-05-29T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Radiology*
publication_short: In *Radiology*

abstract: "Background
Accurate estimation of the malignancy risk of pulmonary nodules at chest CT is crucial for optimizing management in lung cancer screening. Purpose To develop and validate a deep learning (DL) algorithm for malignancy risk estimation of pulmonary nodules detected at screening CT.

Materials and Methods 
In this retrospective study, the DL algorithm was developed with 16 077 nodules (1249 malignant) collected -between 2002 and 2004 from the National Lung Screening Trial. External validation was performed in the following three -cohorts -collected between 2004 and 2010 from the Danish Lung Cancer Screening Trial: a full cohort containing all 883 nodules (65 -malignant) and two cancer-enriched cohorts with size matching (175 nodules, 59 malignant) and without size matching (177 -nodules, 59 malignant) of benign nodules selected at random. Algorithm performance was measured by using the area under the receiver operating characteristic curve (AUC) and compared with that of the Pan-Canadian Early Detection of Lung Cancer (PanCan) model in the full cohort and a group of 11 clinicians composed of four thoracic radiologists, five radiology residents, and two pulmonologists in the cancer-enriched cohorts. 

Results 
The DL algorithm significantly outperformed the PanCan model in the full cohort (AUC, 0.93 [95% CI: 0.89, 0.96] vs 0.90 [95% CI: 0.86, 0.93];   = .046). The algorithm performed comparably to thoracic radiologists in cancer-enriched cohorts with both random benign nodules (AUC, 0.96 [95% CI: 0.93, 0.99] vs 0.90 [95% CI: 0.81, 0.98];   = .11) and size-matched benign nodules (AUC, 0.86 [95% CI: 0.80, 0.91] vs 0.82 [95% CI: 0.74, 0.89];   = .26).

Conclusion
The deep learning algorithm showed excellent performance, comparable to thoracic radiologists, for malignancy risk estimation of pulmonary nodules detected at screening CT. This algorithm has the potential to provide reliable and reproducible malignancy risk scores for clinicians, which may help optimize management in lung cancer screening. © RSNA, 2021   See also the editorial by Tammemägi in this issue."

# Summary. An optional shortened abstract.
summary: A deep learning algorithm for estimating malignancy risk of lung nodules from chest CT scans

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Deep learning for estimating malignancy risk of lung nodules'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

The algorithm can be accessed on [grand-challenge.org](https://grand-challenge.org/algorithms/pulmonary-nodule-malignancy-prediction/)
