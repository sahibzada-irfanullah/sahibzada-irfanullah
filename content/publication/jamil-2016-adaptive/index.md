---
title: "Adaptive thresholding technique for segmentation and juxtapleural nodules inclusion in lung segments"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Muhammad Zia ur Rehman
  - Syed Omer Gilani
  - Syed Irtiza Ali Shah
  - Mohsin Jamil
  - admin
  - Shahid Ikramullah Butt

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - "ORCID: 0000-0003-1659-6040"
  - 'Equal contribution'

date: '2013-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Journal of Bio-Science and Bio-Technology*
publication_short: In *IJBSBT*

abstract: Early diagnosis of lung cancer plays crucial role in the improvement of patients' chances of survival. Computer aided detection (CAD) system has been a groundbreaking step in the timely diagnosis and identification of potential nodules (lesions). CAD system starts detection process by extracting lung regions from CT scan images, this step narrows down the region for detection. Hence saving the time consumption and reducing false positives outside the lung regions that results in the improvement of specificity of system. Proper lung segmentation significantly increases the performance of CAD systems. Different algorithms are presented by various researchers to improve segmentation results. An intensity based approach is presented in this paper for the segmentation of parenchyma and the goal is to achieve reasonable segmentation results in less time. Algorithm used in this paper is based on the Intensity based thresholding which is the fastest method for image segmentation. Images used in this research to analyze algorithm's result are taken from Lung Image Database Consortium (LIDC). Twenty random cases were picked, each having different number of slices (128 to 300). Algorithm is implemented using MatlabR2014 and a system with processor of 2.6 GHz and RAM of 4 GB. Total time taken for a single case of 128 images was 6.3 seconds and hence with an average of 49 milli sec/slice.

# Summary. An optional shortened abstract.
summary: This paper proposes an intensity-based thresholding algorithm for fast lung parenchyma segmentation in CT scans, achieving an average processing time of 49 ms per slice on the LIDC dataset and improving CAD specificity by focusing only on lung regions.

tags:
  - Lung cancer
  - Juxta-pleural nodules
  - Computer aided detection (CAD)
  - segmentation
  - Intensity based thresholding
# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://gvpress.com/journals/IJBSBT/vol8_no5/10.pdf'
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
