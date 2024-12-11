# Sentiment Analysis of Children's and Adult Literature in Classic Texts

## General Information
This project investigates how sentiment differs between children's and adult literature using texts from Project Gutenberg. By analyzing sentiment polarity and emotional categories, the project aims to uncover differences in emotional storytelling techniques and their alignment with the target audience.

---

## Background Information
1. **Emotion and Sentiment in Literature:** Literature mirrors emotional complexity and societal norms. Children's literature often emphasizes positive reinforcement, while adult literature explores broader emotional themes (e.g., happiness, sadness, anger).
2. **Prior Work:** The "Pollyanna hypothesis" suggests that humans have a universal tendency to use positive language more frequently than negative language. This positivity bias has been observed across various text corpora, including literature and everyday communication. Despite this, research has also explored how sentiment varies in different contexts, such as literature, where even tragic themes can exhibit an overall positive tilt.
In the context of sentiment analysis, studies have shown that emotional expression changes over time, particularly during adolescence. Negative sentiment tends to increase with age, while positive sentiment follows a more fluctuating pattern. Sentiment analysis techniques, including machine learning classifiers, are widely used to study how emotions are expressed across different types of texts, such as product reviews, social media, and literary works.
3. **sources:** ([Jacobs 2020](https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2020.574746/full), [Hipson 2019](https://journals.sagepub.com/doi/epub/10.1177/0165025419830248), [Prabowo 2009](https://pdf.sciencedirectassets.com/273584/1-s2.0-S1751157709X00039/1-s2.0-S1751157709000108/main.pdf)).

---

## Research Question and Hypothesis
### Research Question
How does sentiment differ between children's and adult literature in Project Gutenberg's collection?

### Hypothesis
Children's literature contains a higher proportion of positive sentiment compared to adult literature, which features a more diverse and balanced emotional spectrum.

---

## Method
### Dataset
- **Source:** Classic texts from Project Gutenberg.
- **Text Selection:** Gather a list of texts categorized as children's literature and adult literature (for example: works by authors like Lewis Carroll and Charles Dickens for children; Jane Austen and Herman Melville for adults).
- **Criteria for Classification:** Metadata from Project Gutenberg and manual review of content.

### Analysis Steps
1. **Preprocessing:**  
   - Tokenize and clean the texts (SpaCy).  
   - Classify each text into one of the two categories: children’s or adult literature.

2. **Sentiment Analysis:**
   - Use a sentiment analysis tool to measure sentiment polarity (e.g., SpacyTextBlob or Asent).

3. **Comparative Analysis:**
   - Calculate the proportion of positive, negative, and neutral sentiment in each category.
   - Compare the frequency of specific emotional expressions (e.g., happiness, sadness) between children's and adult literature.

### Variables
- **Independent Variable:** Target audience (children, adult).
- **Dependent Variables:**
   - Sentiment polarity (positive, neutral, negative; e.g. range from 1 to -1).

### Tools
- Python libraries for text analysis (e.g. spaCy and SpacyTextBlob).

---

## Expected Outcomes
- Children's literature will exhibit a higher proportion of positive sentiment with frequent use of joy-related words.
- Adult literature will display a broader sentiment spectrum with significant representation of both positive and negative emotions, reflecting more complex emotional narratives.


---
