# BERT-Based Sentiment Analysis for Wheelchair Accessibility in Jakarta Tourism Destinations
## Overview

This repository contains the open dataset and implementation framework developed for an undergraduate thesis focused on aspect-based sentiment analysis (ABSA) of wheelchair accessibility information in 30 tourism destinations in Jakarta. The system applies a multilingual BERT-based model to analyze accessibility-related opinions extracted from tourism reviews. The resulting insights aim to support inclusive tourism by structuring accessibility information for wheelchair users. This repository is released to support transparency, reproducibility, and future accessibility-focused research.

## Dataset Information

The dataset consists of tourism review texts filtered and annotated for wheelchair accessibility sentiment.

### Dataset Characteristics

- Source: Google Maps reviews  
- Languages: Indonesian and English (including code-switching)  
- Annotation: Aspect-based sentiment labeling  
- Classes: Positive, Neutral, Negative  
- Accessibility aspects: ramps, stairs, pathways, lifts, facilities

## Methodology

### Exploratory Data Analysis
Understanding distribution, linguistic patterns, and sentiment balance.

### Text Preprocessing
Noise removal, normalization, and accessibility aspect filtering.

### Model Training
Fine-tuning a multilingual BERT model (XLM-RoBERTa) for aspect-based sentiment classification.

### Evaluation
Performance measured using accuracy, precision, recall, and F1-score.


## Limitations

- Dataset limited to Jakarta tourism destinations  
- Accessibility mentions rely on explicit review content  
- No real-time data updates

## Ethical Considerations

All data originates from publicly available reviews. Personal identifiers are excluded to preserve privacy. The dataset is shared strictly for academic and research purposes.
