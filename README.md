# AI & ML Analysis of Social Media Advocacy for the Banyamulenge Crisis
Dissertation project: AI and Machine Learning for Social Media Advocacy - Banyamulenge Crisis

**Author:** Meghana Kormangala Venkataswamy  
**University:** University of Bradford | 2025 
**Project-Type:** Industry-Based Dissertation

This project explores how AI and Machine Learning analyze YouTube discussions about the Banyamulenge crisis (2010–2025), focusing on sentiment, emotions, topic trends, and misinformation.

---

## 📌 Overview

The study aims to:

- Understand how social media reflects the Banyamulenge crisis.
- Identify sentiment, emotions, and prevalent topics in YouTube comments.
- Detect misinformation and advocacy efforts.
- Explore how AI can support digital advocacy for underrepresented communities.

---

## 🛠 Methodology

**Case Study Approach:**  
Focused on the Banyamulenge community in the Democratic Republic of Congo (DRC).

**Data Source:**  
- YouTube videos (2010–2025) with ≥200 comments.  
- Keywords: `Banyamulenge conflict`, `South Kivu violence`, `Banyamulenge displacement`.

**Data Processing:**  
- Cleaning & normalization (lowercase, remove stopwords, tokenization).  
- Language detection & translation (English, French, Swahili, local languages).  
- Removal of duplicates and bot-like activity.

**Analysis Techniques:**  
- Sentiment Analysis (Positive / Negative / Neutral)  
- Emotion Detection (Anger, Sadness, Fear, Joy, Disgust, Surprise)  
- Topic Modeling (LDA & BERTopic)  
- Misinformation Detection (manual + automatic)

---

## 📊 Data & Results

### 1️⃣ Sentiment & Emotion Trends (2011–2025)

- **Anger:** peaked 80% in 2019, 72% in 2025  
- **Sadness:** peaked 88% in 2015  
- **Fear:** spikes in 2020 (55%) & 2025 (71%)  
- **Joy:** peak at 69% in 2021 (solidarity campaigns)  
- **Disgust:** strong in 2020 (40%) & 2025 (72%)  
- **Surprise:** peak 52% in 2021  
- **Neutral:** low activity years (2011, 2012, 2016)

**Emotion Heatmap:**  
![Emotion Heatmap](images/emotion_heatmap.png)

---

### 2️⃣ Topic Trends

**Dominant Themes Identified:**

1. Identity & belonging  
2. Conflict & displacement  
3. Lack of attention by governments / UN / AU  
4. Misinformation & rumors  
5. Diaspora & support campaigns

**Topic Snapshot (example):**  
![Topic Model Snapshot](images/topic_snapshot.png)

---

### 3️⃣ Misinformation Analysis

**Detected Types:**  
- Delegitimizing claims (Banyamulenge as outsiders)  
- Exaggerated reports (inflated casualties)  
- Rumors of alliances with rebel groups  

**Insight:**  
Misinformation spikes during high-conflict periods, but diaspora activists actively counter it.  

---

## 🔄 Research Workflow

```mermaid
flowchart TD
    A[Video Selection: YouTube 2010-2025] --> B[Data Extraction via YouTube API]
    B --> C[Data Cleaning & Preprocessing]
    C --> D[Sentiment & Emotion Analysis]
    C --> E[Topic Modeling]
    C --> F[Misinformation Detection]
    D & E & F --> G[Visualizations & Results]
