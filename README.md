# Wrappler Wrapped: Temporal Variation in Network Metrics of Articles and Entities

![Header](images/header.png)

## Overview

This repository contains data, images, and Jupyter notebooks related to the paper "Wrappler Wrapped: Temporal Variation in Network Metrics of Articles and Entities." The contents of this repository are organized to facilitate analysis in the field of network science.

## Notebooks

The following Jupyter notebooks are included in this repository:

1. **00-scraping-rappler-articles.ipynb**
   - This notebook is responsible for scraping the data required by subsequent notebooks. The dataset is too large to store in Git, so it should be run first to gather the necessary data.

2. **01-ns-proj-ner.ipynb**
   - This notebook implements Named Entity Recognition (NER) to generate entities for each article. These entities are crucial for the network analysis.

3. **02-cleaning-data.ipynb**
   - This notebook focuses on cleaning the NER results, addressing issues such as Tagalog words incorrectly identified as persons. Clean data is essential for accurate analysis.

4. **03-dynamic-bar-charts.ipynb**
   - Here, you will find code to create dynamic bar charts representing topic trends as GIFs. These visualizations can provide valuable insights into temporal variations.

5. **04-dynamic-articles-network.ipynb**
   - This notebook utilizes topic modeling to label articles to specific topics, facilitating further network analyses. It is a crucial step in understanding the network dynamics.

6. **05-dynamic-entities_network.ipynb**
   - In this notebook, you can perform analyses on entities, including centrality measurements, and generate a temporal GIF illustrating the evolution of central nodes over time.

## Getting Started

To get started with this repository, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/jamwung/temporal-eda-rappler.git
