# The AI Boom: Trends, Impact and Analysis

This repository hosts the analysis for **The AI Boom** project – a comprehensive study of the growth and impact of artificial intelligence over the past decade. The project investigates trends in academic research, public interest and breakthrough innovations that have helped shape the current AI landscape.

## Overview

**Objective:**  
Examine whether the current AI boom could have been predicted by analysing academic research trends and public interest. The study:
- Analyses academic paper datasets (from arXiv and Semantic Scholar) to identify key milestones and shifts in focus.
- Leverages Google Trends data to capture public interest and sentiment around AI-related keywords and services.
- Integrates insights from multiple data sources to draw conclusions about the timing and drivers of the AI revolution.

**Key Findings:**
- A significant surge in AI research and publications preceded the mainstream introduction of AI-powered products.
- Landmark innovations such as the introduction of Transformers, GPT-1 and ChatGPT are closely linked with rapid increases in research output and public interest.
- The growth in AI research is geographically and institutionally concentrated, with the USA, UK and China playing key roles.

## Data Sources

- **Academic Papers:**  
  - Metadata from [arXiv (via Kaggle)](https://www.kaggle.com/datasets/Cornell-University/arxiv/data).

- **Semantic Scholar API:**  
  - Additional citation counts and author affiliations were retrieved using the [Semantic Scholar API](https://api.semanticscholar.org). By using paper IDs (prefixed with `ARXIV:`), this API provided a measure of each paper’s impact within the academic community.

- **Hipo/university-domains-list:**  
  - Country information for academic institutions was obtained using the [Hipo/university-domains-list](https://github.com/Hipo/university-domains-list) via the Python package `universities` (v1.1.0). This enabled efficient mapping of author affiliations to their corresponding countries.

- **Public Interest:**  
  - Google Trends data was collected using the [pytrends](https://github.com/GeneralMills/pytrends) library to capture public interest and sentiment around AI-related keywords and services.


## Repository Contents

- **Presentation:**  
  A detailed project overview and summary of key insights is provided in the PowerPoint file:
  - `AI_boom_Presentation.pdf`

- **Analysis Notebook:**  
  The full data analysis, code and visualisations are available in the Jupyter Notebook:
  - `MainProject_Notebook.ipynb`

- **Supporting Graphs and Data:**  
  Additional Python scripts, Data andGraphs that were used for data processing and visualisation are located in the other directories.
