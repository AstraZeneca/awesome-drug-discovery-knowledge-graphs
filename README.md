# Awesome Drug Discovery Knowledge Graphs

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
![Maturity level-Prototype](https://img.shields.io/badge/Maturity%20Level-Prototype-red)
[![Arxiv](https://img.shields.io/badge/ArXiv-2102.10062-orange.svg)](https://arxiv.org/abs/2102.10062)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

A collection of datasets and associated research papers related to knowledge graphs suitable for use in drug discovery.

<p align="center">
  <img width="400" src="https://github.com/AstraZeneca/awesome-drug-discovery-knowledge-graphs/raw/master/kg-drug-discovery.png">
</p>

## Overview

Drug discovery and development is a complex and costly process. Machine learning approaches are being investigated to help improve the effectiveness and speed of multiple stages of the drug discovery pipeline. Of these, those that use Knowledge Graphs (KG) have promise in many tasks, including drug repurposing, drug toxicity prediction and target gene-disease prioritisation. In a drug discovery KG, crucial elements including genes, diseases and drugs are represented as entities, whilst relationships between them indicate an interaction. However, to construct high-quality KGs, suitable data is required. In this review, we detail publicly available sources suitable for use in constructing drug discovery focused KGs. We aim to help guide machine learning and KG practitioners who are interested in applying new techniques to the drug discovery field, but who may be unfamiliar with the relevant data sources. The datasets are selected via strict criteria, categorised according to the primary type of information contained within and are considered based upon what information could be extracted to build a KG. We then present a comparative analysis of existing public drug discovery KGs and a evaluation of selected motivating case studies from the literature. Additionally, we raise numerous and unique challenges and issues associated with the domain and its datasets, whilst also highlighting key future research directions. We hope this review will motivate KGs use in solving key and emerging questions in the drug discovery domain.

## The Survey Paper

This repository accompanies our survey paper [A Review of Biomedical Datasets Relating to Drug Discovery: A Knowledge Graph Perspective](https://arxiv.org/abs/2102.10062).

Please consider citing the associated paper for this resource if you find it useful:

```
@article{bonner2022review,
  title={A review of biomedical datasets relating to drug discovery: A knowledge graph perspective},
  author={Bonner, Stephen and Barrett, Ian P and Ye, Cheng and Swiers, Rowan and Engkvist, Ola and Bender, Andreas and Hoyt, Charles Tapley and Hamilton, William L},
  journal={Briefings in Bioinformatics},
  volume={23},
  number={6},
  year={2022},
  publisher={Oxford Academic}
}
```

-----------------------------------------------------------------

## Contents

This repository primarily collects together public knowledge graph which could be used for drug discovery. We provide a list of such resources with links to the associated manuscripts, download locations and, wherever possible, the code used to create or update the resources. The list can be found using the link below:

[Drug Discovery Knowledge Graphs](https://github.com/AstraZeneca/awesome-drug-discovery-knowledge-graphs/blob/master/chapters/drug_discovery_kgs.md)


Additionally, we provide separate lists of key biomedical resources which are often used to compose these graphs, as well as some notable applications of KG use within drug discovery: 

1. [Source Datasets](https://github.com/AstraZeneca/awesome-drug-discovery-knowledge-graphs/blob/master/chapters/source_datasets.md)
2. [Biomedical Ontologies](https://github.com/AstraZeneca/awesome-drug-discovery-knowledge-graphs/blob/master/chapters/ontologies.md)
3. [Applications](https://github.com/AstraZeneca/awesome-drug-discovery-knowledge-graphs/blob/master/chapters/applications.md)

-----------------------------------------------------------------

## Note On Publication Version  

This list will continue to evolve as new resources are made available. If you want to view the list which matches the version of the published manuscript, please use this [link.](https://github.com/AstraZeneca/awesome-drug-discovery-knowledge-graphs/releases/tag/v1.0.0)

--------------------------------------------------------------------------------

**License**

- [Apache 2.0](https://github.com/AstraZeneca/awesome-drug-discovery-knowledge-graphs/blob/master/LICENSE)
--------------------------------------------------------------------------------
