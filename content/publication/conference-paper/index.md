---
title: 'R and Bioconductor-based Workflow for Downstream Analysis of LFQ Meat Proteomics Data: Enhancing Reproducibility in Meat Proteomics Research'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'

date: '2024-12-07T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-12-07T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *VIBE/ICBG 2024 Conference*
publication_short: In *VIBE/ICBG 2024*

abstract: 'Proteomics have been extensively used in meat science to understand the biochemistry of meat quality. Identified and quantified proteomics data obtained through processing with analytical software tools, such as Mascot and Progenesis QI, among others, serve as a common starting point for meat scientists to analyze shotgun proteomic data. However, a standardized workflow for the downstream statistical analysis and visualization of these factorial design datasets is lacking. The workflow was developed using several R and Bioconductor packages including Tidyverse, UniprotR, QFeature, limma, EFS, ggplot2, pheatmap, ggvenn, and UpSetR, along with custom functions. The methodology is demonstrated using an experimental shotgun dataset preprocessed via Mascot and Progenesis QI. This dataset was derived from postmortem muscle tissues from a 2×4 factorial study of cattle reared under two slaughter conditions and four feeding regimes. This workflow produced a result table with the gene name, UniProt accession, log2 fold change, p-value, and the corresponding adjusted p-value from the LFQ data. Publication-quality Venn diagrams, UpSet plots, volcano plots, and heat maps were generated. Dimensional reduction techniques such as PCA, t-SNE, and UMAP were integrated into the workflow. In addition, eight distinct feature selection techniques based on ensemble learning were applied using the EFS package, and the results were compared with differentially abundant proteins and visualized using a volcano plot. To enhance the readability, we implemented a strategy to present the correlation of large datasets more effectively. This R and Bioconductor-based workflow presents a consolidated resource of selected tools that facilitates downstream processing, statistical evaluation, and comprehensive visualization of shotgun proteomic data, thereby potentially enabling meat science researchers to address specific biological questions.'

# Summary. An optional shortened abstract.
summary: An R and Bioconductor-based workflow was developed for standardized statistical analysis and visualization of shotgun proteomic data in meat science. The workflow integrates tools for dimensional reduction, feature selection, and visualization, enabling researchers to effectively analyze and interpret proteomic datasets from factorial design studies.

tags:
  - Proteomics

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://vibe-icbg.com/VIBE_ICBG_Abstract_Book.pdf'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: '' #'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
