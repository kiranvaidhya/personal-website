---
title: 'Automated Assessment of COVID-19 Reporting and Data System and Chest CT Severity Scores in Patients Suspected of Having COVID-19 Using Artificial Intelligence'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Nikolas Lessmann
  - Clara I. Sánchez
  - Ludo Beenen
  - Luuk H. Boulogne
  - Monique Brink
  - Erdi Calli
  - Jean-Paul Charbonnier
  - Ton Dofferhoff
  - Wouter M. van Everdingen
  - Paul K. Gerke
  - Bram Geurts
  - Hester A. Gietema
  - Miriam Groeneveld
  - Louis van Harten
  - Nils Hendrix
  - Ward Hendrix
  - Henkjan J. Huisman
  - Ivana Išgum
  - Colin Jacobs
  - Ruben Kluge
  - Michel Kok
  - Jasenko Krdzalic
  - Bianca Lassen-Schmidt
  - Kicky van Leeuwen
  - James Meakin
  - Mike Overkamp
  - Tjalco van Rees Vellinga
  - Eva M. van Rikxoort
  - Riccardo Samperna
  - Cornelia Schaefer-Prokop
  - Steven Schalekamp
  - Ernst Th. Scholten
  - Cheryl Sital
  - J. Lauran Stöger
  - Jonas Teuwen
  - admin
  - Coen de Vente
  - Marieke Vermaat
  - Weiyi Xie
  - Bram de Wilde
  - Mathias Prokop
  - Bram van Ginneken

date: '2020-07-30T00:00:00Z'
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

abstract: "The coronavirus disease 2019 (COVID-19) pandemic has spread across the globe with alarming speed, morbidity, and mortality. Immediate triage of patients with chest infections suspected to be caused by COVID-19 using chest CT may be of assistance when results from definitive viral testing are delayed. Purpose: To develop and validate an artificial intelligence (AI) system to score the likelihood and extent of pulmonary COVID-19 on chest CT scans using the COVID-19 Reporting and Data System (CO-RADS) and CT severity scoring systems. Materials and Methods: The CO-RADS AI system consists of three deep-learning algorithms that automatically segment the five pulmonary lobes, assign a CO-RADS score for the suspicion of COVID-19, and assign a CT severity score for the degree of parenchymal involvement per lobe. This study retrospectively included patients who underwent a nonenhanced chest CT examination because of clinical suspicion of COVID-19 at two medical centers. The system was trained, validated, and tested with data from one of the centers. Data from the second center served as an external test set. Diagnostic performance and agreement with scores assigned by eight independent observers were measured using receiver operating characteristic analysis, linearly weighted κ values, and classification accuracy. Results: A total of 105 patients (mean age, 62 years ± 16 [standard deviation]; 61 men) and 262 patients (mean age, 64 years ± 16; 154 men) were evaluated in the internal and external test sets, respectively. The system discriminated between patients with COVID-19 and those without COVID-19, with areas under the receiver operating characteristic curve of 0.95 (95% CI: 0.91, 0.98) and 0.88 (95% CI: 0.84, 0.93), for the internal and external test sets, respectively. Agreement with the eight human observers was moderate to substantial, with mean linearly weighted κ values of 0.60 ± 0.01 for CO-RADS scores and 0.54 ± 0.01 for CT severity scores. Conclusion: With high diagnostic performance, the CO-RADS AI system correctly identified patients with COVID-19 using chest CT scans and assigned standardized CO-RADS and CT severity scores that demonstrated good agreement with findings from eight independent observers and generalized well to external data."

# Summary. An optional shortened abstract.
summary: Automatic CORADS score prediction on chest CT with deep learning

tags: [Deep Learning, COVID-19, CT]

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
  caption: 'CORADS-AI'
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

The algorithm can be accessed on [grand-challenge.org](https://grand-challenge.org/algorithms/corads-ai/)
