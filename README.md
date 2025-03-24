# NutriLensAI
AI-powered tool that automates extraction and analysis of nutritional information from food labels using OCR, NLP, and LLMs. Provides accurate, personalized dietary insights tailored to user preferences, simplifying health management and empowering informed food choices.

# Nutrient Analysis from Food Label Images Using Data-Driven Models

AI-powered tool developed as a term project for CIS 667: Introduction to Artificial Intelligence. It automates extraction and analysis of nutritional information from food labels using OCR, NLP, and LLMs, delivering personalized dietary insights to simplify health management and empower informed food choices.

## Project Overview

With the rising trend of health consciousness, this project automates the extraction and analysis of nutritional information from food labels and recipe images using advanced AI techniques. By leveraging Optical Character Recognition (OCR), Natural Language Processing (NLP), and Large Language Models (LLMs), we aim to provide users with accurate and tailored nutritional insights, empowering better-informed dietary decisions.

## Features

- **Automated Text Extraction**: Uses OCR to extract textual information from food labels.
- **Nutritional Information Parsing**: NLP to categorize and interpret data into structured formats.
- **Personalized Dietary Insights**: LLM-based analysis tailored to user-specific dietary needs.
- **Prompt Engineering**: Refines model outputs for improved accuracy and relevance.
- **User-Friendly Outputs**: JSON-formatted results for seamless integration with other systems.

## Methodology

The project integrates various AI techniques:

1. **OCR (EasyOCR)**:
   - Converts images of food labels into machine-readable text.
   - Extracts nutritional facts using robust text detection and recognition models.
2. **NLP**:
   - Tokenizes and processes extracted text.
   - Applies Named Entity Recognition (NER) to identify nutrients, ingredients, and measurements.
3. **LLMs**:
   - Uses lightweight models (e.g., Llama-3.2-1B) for contextual analysis and recommendations.
   - Employs prompt engineering to refine outputs based on dietary constraints.

![NutriLensAI_process](https://github.com/user-attachments/assets/03b49dcd-7510-4142-b45c-d3cd905be384)


## Challenges and Solutions

- **Challenge**: Locating and isolating nutritional facts in complex layouts.
  - **Solution**: Integrated LLMs for context-aware parsing and analysis.
- **Challenge**: Standardizing diverse text structures from OCR.
  - **Solution**: JSON formatting for consistency and ease of use.

## Results

The system successfully extracts nutritional data and provides customized insights:
- Example output includes calorie counts, sugar content, and dietary recommendations.
- Highlights positive and negative aspects based on individual dietary preferences.

## Future Work

- Develop a mobile or web application for broader accessibility.
- Expand capabilities for real-time analysis and multilingual datasets.
- Integrate comprehensive diet plans and meal suggestions.

## Implementation

- **Environment**: Google Colab
- **Key Libraries**: 
  - [EasyOCR](https://github.com/JaidedAI/EasyOCR)
  - [PyTorch](https://pypi.org/project/torch/)
  - [Transformers](https://pypi.org/project/transformers/)
  - [Json](https://pypi.org/project/jsons/)
  - [Aisuite](https://pypi.org/project/aisuite/)

Google Colab Implementation: [Link to Notebook](https://colab.research.google.com/drive/1hssG0A63Darm7yq_Ort5ud755MzsZQEL?usp=sharing)

## Team Members

- Aryan Nilesh Sadvelkar ([Email](mailto:asadvelk@syr.edu))
- Prabin Raj Shrestha ([Email](mailto:prbn.ms@gmail.edu) | [Website](https://prbn.info))
- Peiying Chen ([Email](mailto:pchen21@syr.edu))

## References

- [EasyOCR GitHub](https://github.com/JaidedAI/EasyOCR)
- [3Blue1Brown YouTube - Transformers](https://www.youtube.com/watch?v=wjZofJX0v4M&t=1173s)
- [OpenAI GPT-4 Architecture](https://semianalysis.com/2023/07/10/gpt-4-architecture-infrastructure)
