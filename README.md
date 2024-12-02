# Course-Recommendation-System
A recommendation system for courses built using Udemy's course dataset. This system leverages natural language processing (NLP) techniques and similarity algorithms to suggest relevant courses based on user input.

![Python](https://img.shields.io/badge/Python-3.9-blue.svg) ![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-green.svg) ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-NLP-orange.svg)

---

## **Features**
✅ **Dataset Exploration**:
- Includes course titles, descriptions, subscriber counts, reviews, and more.
- Explores relationships between course features and popularity metrics.

✅ **Text Preprocessing**:
- Cleans course titles by removing stopwords and special characters.
- Tokenizes and vectorizes text data.

✅ **Recommendation Engine**:
- Uses **Cosine Similarity** and **Linear Similarity** to find similar courses.
- Ranks and recommends the top N courses based on similarity scores.

✅ **Customizable Input**:
- Users can search courses by keywords or entire titles for tailored recommendations.

---

**How It Works**

1️⃣ Data Preprocessing:

Removes noise, stopwords, and special characters.
Tokenizes and vectorizes course titles using CountVectorizer and TfidfVectorizer.

2️⃣ Similarity Calculation:

Computes cosine similarity between course vectors to measure relevance.
Builds a similarity matrix for all courses.

3️⃣ Recommendation:

Input a course or keyword, and the system finds the top N similar courses.
Filters courses based on similarity scores and user-defined thresholds.

**Example Usage**

Input:

Search Query: "Python for Finance"

Output:

Top 3 Recommendations:

"Python Algo Trading: Sentiment Trading with News"

"Stock Technical Analysis with Python"

"Python and Django Full Stack Developer Bootcamp"

