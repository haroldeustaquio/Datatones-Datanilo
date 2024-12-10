# Alan García Posts

## Overview

The analysis focuses on comments and sentiments expressed in posts related to Alan García's death. The goal is to understand how society perceived this event and identify the emotions that dominated the public discussion.

**Content**

- [Text Processing](#text-processing)
- [Sentiment Analysis](#sentiment-analysis)
- [Visualization](#visualization)

---

## Text Processing

1. **Data Loading and Exploration**
   - Data was loaded from JSON/CSV files containing social media comments.
   - Initial exploration was conducted to understand the structure and content of the dataset.

2. **Data Cleaning**
   - Columns were renamed and reordered for consistency.
   - Redundant and irrelevant columns were dropped.
   - Missing values and duplicate records were identified and removed.

3. **Text Normalization**
   - Punctuation and accents were removed from text to standardize input.
   - Stopwords (common words with little meaning, like "the" or "and") were removed.
   - Text was converted to lowercase to avoid case sensitivity issues.

4. **Emoji Handling**
   - A dictionary of emojis and their meanings was created and applied to the text.
   - Emojis were replaced with corresponding descriptive words to retain sentiment information.

5. **Text Enhancement**
   - Sentences were reconstructed after cleaning to prepare for sentiment analysis.
   - Specific text patterns (e.g., hashtags, mentions) were preserved where relevant.

6. **Dataset Finalization**
   - Final cleaned data was saved for sentiment analysis, ensuring integrity and readiness for modeling.

---

## Sentiment Analysis

1. **Sentiment Scoring with NRC Lexicon**
   - The NRC (National Research Council) Emotion Lexicon was used to classify text into specific emotions.
   - Each post was scored based on the presence of words associated with these emotions.

2. **Frequent Sentiment Detection**
   - For each post, the most frequent sentiment was identified as the dominant sentiment, providing a concise representation of the overall emotional tone.

---

## Visualization

### Comments Analysis
- **Number of Comments by Context**: Tracks how many comments are associated with specific contexts related to Alan García.
- **Number of Comments by Date**: Displays the volume of comments over time.
- **Timeline of Comments by Date and Context**: Provides a combined view of comments across dates and specific contexts.

### Sentiment Analysis
- **Number of Comments by Sentiment**: Shows the distribution of comments classified as positive, negative, or neutral.
- **Number of Comments by Context**: Highlights sentiment distribution within specific contexts.
- **Most Frequent Words**: Visualizes commonly used words, emphasizing those contributing most to the identified sentiments.

<p align="center">
  <img src="https://github.com/user-attachments/assets/f5a58b9a-7a1d-471c-b159-2de73915a6e9" alt="Architecture">
</p>

<p align="center">
  <em>Figure 1: Main Cover</em>
</p>

---

<div align="center"> 
  <em> 
    We believe in the power of collaboration. If you have ideas, suggestions, or improvements, feel free to open an issue or submit a pull request. Let’s make this project even better—your contributions are always welcome! 
  </em> 
</div>

