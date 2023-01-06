---
title: 'Automated COVID-19 Grading With Convolutional Neural Networks in Computed Tomography Scans: A Systematic Comparison'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Coen de Vente
  - Luuk H. Boulogne
  - admin
  - Cheryl Sital
  - Nikolas Lessmann
  - Colin Jacobs
  - Clara I. Sánchez
  - Bram van Ginneken

date: '2021-10-08T00:00:00Z'
doi: '10.1109/TAI.2021.3115093'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-05-29T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Artificial Intelligence*
publication_short: In *IEEE TAI*

# Summary. An optional shortened abstract.
summary: A systematic investigation of algorithm components of convolutional neural networks for grading chest CT scans of patients suspected with COVID-19

tags: [Deep Learning, COVID-19, CT]

# Display this page in the Featured widget?
featured: false

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
  caption: 'Systematic investigation of CORADS-AI'
  focal_point: ''
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
# slides: example
---

# Impact Statement
Impact Statement—Applied artificial intelligence (AI) research focuses disproportionately on novel architecture modifications that do not necessarily generalize to other datasets, while neglecting systematic comparisons between commonly used algorithm components. This inhibits the deployment of AI for real-world applications. For automatic COVID-19 grading specifically, attention for compatibility of AI with clinical workflow is lacking. This paper presents a systematic investigation of COVID-19 grading algorithm components using a large publicly available dataset. The results are published in an online challenge. These contributions speed up the development of AI applications for COVID-19 grading by establishing insights into the components of such applications and by allowing applications produced by future research to be compared in a fair manner. The adherence to a standardized COVID-19 grading system may increase the compatibility between AI and clinical workflow.

# Abstract
Amidst the ongoing pandemic, the assessment of computed tomography (CT) images for COVID-19 presence can exceed the workload capacity of radiologists. Several studies addressed this issue by automating COVID-19 classification and grading from CT images with convolutional neural networks (CNNs). Many of these studies reported initial results of algorithms that were assembled from commonly used components. However, the choice of the components of these algorithms was often pragmatic rather than systematic and systems were not compared to each other across papers in a fair manner. We systematically investigated the effectiveness of using 3-D CNNs instead of 2-D CNNs for seven commonly used architectures, including DenseNet, Inception, and ResNet variants. For the architecture that performed best, we furthermore investigated the effect of initializing the network with pretrained weights, providing automatically computed lesion maps as additional network input, and predicting a continuous instead of a categorical output. A 3-D DenseNet-201 with these components achieved an area under the receiver operating characteristic curve of 0.930 on our test set of 105 CT scans and an AUC of 0.919 on a publicly available set of 742 CT scans, a substantial improvement in comparison with a previously published 2-D CNN. This article provides insights into the performance benefits of various components for COVID-19 classification and grading systems. We have created a challenge on grand-challenge.org to allow for a fair comparison between the results of this and future research.