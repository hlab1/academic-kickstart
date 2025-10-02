---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Robust discovery of gene regulatory networks from single-cell gene expression data by Causal Inference Using Composition of Transactions"
authors: ["Abbas&nbsp;Shojaee","**Shao&hyphen;shan Carol Huang**"]
date: 2023-11-01
doi: "10.1093/bib/bbad370"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-11-02T00:00:01-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Briefings in Bioinformatics*"
publication_short: "*Brief Bioinform*"

abstract: "Gene regulatory networks (GRNs) drive organism structure and functions, so the discovery and characterization of GRNs is a major goal in biological research. However, accurate identification of causal regulatory connections and inference of GRNs using gene expression datasets, more recently from single-cell RNA-seq (scRNA-seq), has been challenging. Here we employ the innovative method of Causal Inference Using Composition of Transactions (CICT) to uncover GRNs from scRNA-seq data. The basis of CICT is that if all gene expressions were random, a non-random regulatory gene should induce its targets at levels different from the background random process, resulting in distinct patterns in the whole relevance network of gene–gene associations. CICT proposes novel network features derived from a relevance network, which enable any machine learning algorithm to predict causal regulatory edges and infer GRNs. We evaluated CICT using simulated and experimental scRNA-seq data in a well-established benchmarking pipeline and showed that CICT outperformed existing network inference methods representing diverse approaches with many-fold higher accuracy. Furthermore, we demonstrated that GRN inference with CICT was robust to different levels of sparsity in scRNA-seq data, the characteristics of data and ground truth, the choice of association measure and the complexity of the supervised machine learning algorithm. Our results suggest aiming at directly predicting causality to recover regulatory relationships in complex biological networks substantially improves accuracy in GRN inference."

# Summary. An optional shortened abstract.
#summary: ""

#tags: []
#categories: []
featured: true
share: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter
links: [
{name: "PubMed",url: "https://pubmed.ncbi.nlm.nih.gov/37897702"},
{name: "View at journal",url: "https://academic.oup.com/bib/article-lookup/doi/10.1093/bib/bbad370"}
]

#url_pdf:
url_code: "https://github.com/hlab1/scRNAseqWithCICT"
url_dataset: "https://zenodo.org/doi/10.5281/zenodo.8025871"
#url_poster:
#url_project:
#url_slides:
#url_source:
#url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
#image:
#  caption: ""
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: ""
---
