# AIML-Project
# 🎬 Rashmi Recommends — Movie Recommendation Engine

A streamlined, multi-method recommendation system built using the MovieLens dataset. This app offers content-based, collaborative, and genre-driven suggestions — all through an interactive Streamlit interface.

---

## 📦 What It Does

Users select a movie, and the system returns recommendations using:

- 🔖 **Tag-Based Content Filtering** – via tag relevance scores from `genome_scores.csv`
- 👥 **Collaborative Filtering** – using item-based cosine similarity over `ratings.csv`
- 🎭 **Genre-Based Filtering** – powered by TF-IDF on the `genres` column in `movie.csv`

Each technique provides different yet complementary perspectives on what users might enjoy watching next.

---

## 🚀 Try It Out

To run locally:

```bash
git clone https://github.com/Rashmi12-coder/AIML-Project.git
cd AIML-Project
streamlit run cleaned_recommender_app.py

