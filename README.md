# Nihonbashi Landscape Image Analysis

This repository contains the R scripts used for the temporal co-occurrence analysis conducted in the master's thesis research on the Nihonbashi district in Tokyo.

## Research Objective

The analysis examines how the landscape image associated with Nihonbashi has changed over time by analyzing the co-occurrence of key terms in historical documents.

Particular attention is given to the shift in landscape perception from the traditional river-based image ("Nihonbashi River") to the modern infrastructure-dominated image ("elevated expressway").

## Data Source

Bibliographic data were collected from the National Diet Library (NDL) Search system.
Documents containing the keyword "Nihonbashi" were retrieved and analyzed to identify co-occurrence with selected related terms.

## Method

1. Bibliographic records containing the keyword **"Nihonbashi"** were retrieved from the NDL Search API.
2. Co-occurrences with selected terms (e.g., *Nihonbashi River*, *elevated highway*) were identified.
3. Annual frequencies of co-occurrence were calculated.
4. Co-occurrence rates were computed as the proportion of documents containing both terms relative to the total number of Nihonbashi-related documents.
5. Temporal trends were visualized using line graphs.

## Visualization

The resulting figure shows the long-term transition of landscape imagery related to Nihonbashi from 1911 to 2025.

Two major co-occurrence patterns are compared:
- Nihonbashi × Nihonbashi River
- Nihonbashi × Elevated Highway

Key historical events related to urban development and infrastructure construction are annotated on the timeline.

## Environment
- Google Colab (R runtime)
- R packages: tidyverse, httr, xml2, readr, dplyr, ggplot2

## Author

Yizhou Zhang  
Graduate School of Horticulture  
Chiba University
