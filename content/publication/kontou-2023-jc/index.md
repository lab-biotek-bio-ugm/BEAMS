---
title: 'UmetaFlow: an untargeted metabolomics workflow for high-throughput data processing
  and analysis'
authors:
- Eftychia E Kontou
- Axel Walter
- Oliver Alka
- Julianus Pfeuffer
- Timo Sachsenberg
- Omkar S Mohite
- Matin Nuhamunada
- Oliver Kohlbacher
- Tilmann Weber
date: '2023-05-01'
publishDate: '2024-11-27T20:04:27.577938Z'
publication_types:
- article-journal
publication: '*J. Cheminform.*'
abstract: Metabolomics experiments generate highly complex datasets, which are time
  and work-intensive, sometimes even error-prone if inspected manually. Therefore,
  new methods for automated, fast, reproducible, and accurate data processing and
  dereplication are required. Here, we present UmetaFlow, a computational workflow
  for untargeted metabolomics that combines algorithms for data pre-processing, spectral
  matching, molecular formula and structural predictions, and an integration to the
  GNPS workflows Feature-Based Molecular Networking and Ion Identity Molecular Networking
  for downstream analysis. UmetaFlow is implemented as a Snakemake workflow, making
  it easy to use, scalable, and reproducible. For more interactive computing, visualization,
  as well as development, the workflow is also implemented in Jupyter notebooks using
  the Python programming language and a set of Python bindings to the OpenMS algorithms
  (pyOpenMS). Finally, UmetaFlow is also offered as a web-based Graphical User Interface
  for parameter optimization and processing of smaller-sized datasets. UmetaFlow was
  validated with in-house LC-MS/MS datasets of actinomycetes producing known secondary
  metabolites, as well as commercial standards, and it detected all expected features
  and accurately annotated 76% of the molecular formulas and 65% of the structures.
  As a more generic validation, the publicly available MTBLS733 and MTBLS736 datasets
  were used for benchmarking, and UmetaFlow detected more than 90% of all ground truth
  features and performed exceptionally well in quantification and discriminating marker
  selection. We anticipate that UmetaFlow will provide a useful platform for the interpretation
  of large metabolomics datasets.
tags:
- Analysis; High-throughput workflow; Processing; Software; Untargeted metabolomics
---
