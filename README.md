# 🎬 Movie Review Sentiment Analysis
A comprehensive machine learning project for sentiment analysis of movie reviews using advanced NLP techniques and transformer models.

## 📋 Project Overview
This project implements a complete sentiment analysis pipeline for IMDb movie reviews, featuring advanced preprocessing, multiple prompt engineering strategies, and robust evaluation methodologies. Built as part of an ML internship assignment, it demonstrates professional-grade machine learning practices.

## Technical Approach

1. Data Preprocessing Pipeline
  * Contraction Expansion: "won't" → "will not"
  * Sentiment Preservation: Maintains emphasis markers (!!)
  * Negation Handling: Preserves "not", "never", etc.
  * Lemmatization: Word normalization
  * Stop Word Filtering: Removes noise while keeping sentiment indicators

2. Model Architecture

  * Primary Model: DistilBERT-base-uncased-finetuned-sst-2-english
  * Fallback Models: RoBERTa, BERT-multilingual
  * Ensemble Ready: Framework for combining multiple models

3. Prompt Engineering Strategies
   
  * Direct Classification: Simple sentiment labeling
  * Few-Shot Learning: Example-based learning
  * Chain-of-Thought: Step-by-step reasoning
  * Contextual Analysis: Professional critic framing

## Technologies Used

  * Machine Learning: Transformers (Hugging Face), scikit-learn
  * NLP Processing: NLTK
  * Data Science: Pandas, NumPy
  * Visualization: Matplotlib, Seaborn
  * Development: Google Colab, Python 3.8+

## Dataset Information

  * Source: IMDb Movie Reviews Dataset (50,000 reviews)
  * Classes: Binary (Positive/Negative)
  * Balance: 50-50 split
  * Text Length: 100-2000 characters average
  * Language: English

## Error Analysis Insights

1. Common Misclassifications:

  * Sarcastic Reviews: "Oh great, another superhero movie..."
  * Mixed Sentiment: "Great acting but terrible plot"
  * Subtle Negatives: "The movie was fine, I guess..."
  * Context-Dependent: Genre-specific comparisons

2. Solutions Implemented:

  * Enhanced sarcasm detection through emphasis preservation
  * Better handling of mixed sentiment through advanced preprocessing
  * Improved negation detection and context understanding

## Future Improvements

   * Ensemble Methods: Combine multiple model predictions
   * Custom Fine-tuning: Domain-specific model adaptation
   * Multi-class Classification: Neutral, Very Positive, Very Negative
   * Real-time API: Flask/FastAPI deployment
   * Interactive Dashboard: Streamlit web interface

## Assignment Requirements

This project fulfills all ML internship assignment criteria:

  * Part 1: NLP & Dataset Preparation
  * Part 2: Prompt Engineering & Model Interaction
  * Part 3: Model Evaluation (Achieved 87.00% accuracy)
  * Part 4: Troubleshooting & Improvement Analysis

## Acknowledgments

  * IMDb Dataset: Large Movie Review Dataset v1.0
  * Hugging Face: Pre-trained transformer models
  * Fallon Studio: Internship opportunity and guidance
  * Open Source Community: Various libraries and tools used

## Contact

- Author: Allwin Raja
- Email: allwin10raja@gmail.com
- LinkedIn: https://www.linkedin.com/in/allwin-raja/
