---
title: 'Prior CT Improves Deep Learning for Malignancy Risk Estimation of Screening-detected Pulmonary Nodules'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tajwar Abrar Aleef
  - Ernst Scholten
  - Zaigham Saghir
  - Mario Silva
  - Nicola Sverzellati
  - Ugo Pastorino
  - Bram van Ginneken
  - Mathias Prokop
  - Colin Jacobs

date: '2023-08-01T00:00:00Z'
doi: '10.1148/radiol.223308'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-08-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Radiology*
publication_short: In *Radiology*

# Summary. An optional shortened abstract.
summary: Prior CT improves deep learning for estimating lung nodule malignancy risk

tags: [Deep Learning, Lung Cancer, Lung Nodules, CT]

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
  caption: 'Deep learning for estimating malignancy risk of lung nodules using prior CT'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - lung-nodule-analysis

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

## Background
Prior chest CT provides valuable temporal information (eg, changes in nodule size or appearance) to accurately estimate malignancy risk.

## Purpose
To develop a deep learning (DL) algorithm that uses a current and prior low-dose CT examination to estimate 3-year malignancy risk of pulmonary nodules.

## Materials and Methods 
In this retrospective study, the algorithm was trained using National Lung Screening Trial data (collected from 2002 to 2004), wherein patients were imaged at most 2 years apart, and evaluated with two external test sets from the Danish Lung Cancer Screening Trial (DLCST) and the Multicentric Italian Lung Detection Trial (MILD), collected in 2004–2010 and 2005–2014, respectively. Performance was evaluated using area under the receiver operating characteristic curve (AUC) on cancer-enriched subsets with size-matched benign nodules imaged 1 and 2 years apart from DLCST and MILD, respectively. The algorithm was compared with a validated DL algorithm that only processed a single CT examination and the Pan-Canadian Early Lung Cancer Detection Study (PanCan) model.

## Results 
The training set included 10 508 nodules (422 malignant) in 4902 trial participants (mean age, 64 years ± 5 [SD]; 2778 men). The size-matched external test sets included 129 nodules (43 malignant) and 126 nodules (42 malignant). The algorithm achieved AUCs of 0.91 (95% CI: 0.85, 0.97) and 0.94 (95% CI: 0.89, 0.98). It significantly outperformed the DL algorithm that only processed a single CT examination (AUC, 0.85 [95% CI: 0.78, 0.92; _P_ = .002]; and AUC, 0.89 [95% CI: 0.84, 0.95; _P_ = .01]) and the PanCan model (AUC, 0.64 [95% CI: 0.53, 0.74; _P_ < .001]; and AUC, 0.63 [95% CI: 0.52, 0.74; _P_ < .001]).

## Conclusion
A DL algorithm using current and prior low-dose CT examinations was more effective at estimating 3-year malignancy risk of pulmonary nodules than established models that only use a single CT examination.

## Algorithm
The algorithm can be accessed on [grand-challenge.org](https://grand-challenge.org/algorithms/temporal-nodule-analysis/)
