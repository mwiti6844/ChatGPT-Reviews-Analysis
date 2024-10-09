# ChatGPT Reviews Analysis

This repository contains a project focused on analyzing user reviews of ChatGPT using natural language processing (NLP) techniques such as sentiment analysis, n-gram extraction, and Net Promoter Score (NPS). The goal of this analysis is to understand user feedback, identify common themes, and improve the user experience.

## Project Overview

The analysis is based on a dataset of user reviews for ChatGPT, including the review text, ratings, and review dates. The following key tasks were performed:

1. **Sentiment Analysis**:  
   Used a pre-trained transformer model from Hugging Face to classify user reviews into three categories:
   - Positive
   - Neutral
   - Negative

2. **N-gram Extraction**:  
   Extracted common phrases (bigrams and trigrams) from positive, neutral, and negative reviews to identify the most frequently mentioned features, complaints, and feedback.

3. **Net Promoter Score (NPS) Calculation**:  
   Calculated the NPS to gauge customer satisfaction. The reviews were categorized as:
   - **Promoters**: Users who rated 5 stars
   - **Passives**: Users who rated 4 stars
   - **Detractors**: Users who rated 0-3 stars  
   The overall NPS score was **64.35**, indicating strong customer loyalty.

4. **Thematic Analysis**:  
   Identified common themes in promoter, passive, and detractor reviews to understand what aspects of ChatGPT users love, where improvements can be made, and what issues detractors face.

5. **Visualization**:  
   Visualized sentiment trends over time, common phrases in reviews, and the distribution of ratings.

## Key Findings

- **Promoters**:  
  Users who rated ChatGPT highly appreciated its accuracy, ease of use, and the effectiveness of its AI capabilities. Common positive phrases included “great app,” “amazing tool,” and “very helpful.”
  
- **Detractors**:  
  Detractors frequently mentioned issues such as slow response times, errors, and bugs. Common negative phrases included “doesn’t work,” “slow response,” and “error message.”

- **Passives**:  
  Passives generally found ChatGPT useful but mentioned minor issues, indicating that improvements in performance and feature offerings could convert them into promoters.

## Applications Across Different Fields

The techniques and methods used in this project can be applied across various fields to gain insights from user feedback and improve product offerings. Here are some potential applications:

1. **Product Development**:  
   Understanding user reviews helps product managers prioritize features and fix common bugs, leading to more user-centered development and higher customer satisfaction.

2. **Customer Experience**:  
   Sentiment analysis and NPS metrics are valuable for customer service teams, allowing them to respond to negative feedback, engage with detractors, and reduce churn.

3. **Marketing**:  
   By identifying common positive phrases and themes, marketing teams can highlight key product features that users love, improving messaging and branding strategies.

4. **Education**:  
   Sentiment analysis can be used to understand student feedback in online learning platforms. Educational institutions can improve the quality of their services based on real-time feedback.

5. **Healthcare**:  
   In healthcare applications, sentiment analysis can be applied to patient reviews and feedback to improve service delivery, patient satisfaction, and overall healthcare outcomes.

6. **E-commerce**:  
   Similar techniques can be used in e-commerce to analyze product reviews, identify common customer complaints, and improve product offerings based on customer feedback.

## Tools and Libraries Used

- **Python**
- **Transformers** (Hugging Face for sentiment analysis)
- **scikit-learn** (for N-gram extraction and vectorization)
- **pandas** (data manipulation)
- **plotly** (for data visualization)
- **Latent Dirichlet Allocation (LDA)** (optional for topic modeling)

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ChatGPT-Reviews-Analysis.git
