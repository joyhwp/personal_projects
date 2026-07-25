# IMDB Movie Review Sentiment Analysis

## Overview
Built an NLP model to predict positive/negative sentiment from IMDB movie review text, and derived business insights applicable to the film industry based on the results.

## Data
- **Source**: IMDB Movie Review Dataset
- **Columns**: `review` (review text), `sentiment` (label: positive/negative)

## Approach

**1. Preprocessing & EDA**
- Cleaned and tokenized review text
- Visualized word frequency and sentiment distribution to identify preliminary patterns

**2. Sentiment Modeling**
- Applied multiple sentiment classification approaches and compared their performance using Confusion Matrix, Precision, Recall, and F1-score
- **Final model: BERT**, selected for its bidirectional encoding structure. During EDA, the word "not" appeared frequently in positive reviews (e.g., "not bad at all" — negative at the word level, but positive in actual meaning), making a context-aware model necessary. BERT achieved the highest performance (Accuracy ≈ 0.87, F1-score ≈ 0.87) compared to rule-based models.

**3. Business Insight**

Key positive keywords: *love story, real life, special effects, new york, highly recommend, black white, sci-fi* — reflecting emotional resonance, relatability, and production/visual quality.

Key negative keywords: *low budget, waste money, worst ever, main character, high school* — reflecting concerns about production quality, character development, and story structure.

**Insights by function:**
- **Production/Studio**: Investing in emotionally immersive storytelling and visual effects can maximize positive audience response. Frequent complaints about "low budget" and "special effects" suggest a need for stronger visual quality control and post-production investment.
- **Marketing**: Ad copy and trailers can leverage emotionally resonant phrases identified from positive reviews (e.g., messaging centered on "a story that feels more real than reality" or "stunning visual quality"), while addressing budget perception concerns by emphasizing direction and acting quality.
- **Screenwriting**: Recurring negative mentions of "main character" and story-related terms point to a need for stronger character development and narrative structure.
- **Product/Platform**: Sentiment intensity could be used as a feature for box office prediction or recommendation systems — e.g., distinguishing "strongly loved" vs. "strongly disliked" films for more nuanced content recommendations.

## Tech Stack
`Python` `NLP` `BERT` `scikit-learn`

📎 [View Code](./01_NLP_IMDB_Sentiment_Analysis/nlp_imdb_sentiment__analysis.ipynb)
