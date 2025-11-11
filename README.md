# 🎬 Movie Recommendation System

The **Movie Recommendation System** is a machine learning project that suggests movies similar to a given title based on their content.  
It uses **Natural Language Processing (NLP)** and **cosine similarity** to analyze various features of movies such as genres, overviews, keywords, and cast information.  
The system recommends movies that share the most similar characteristics, providing users with intelligent, personalized movie suggestions.

---

## 🧠 Project Description

With thousands of movies released every year, users often struggle to decide what to watch next.  
This project solves that problem by building a **content-based recommendation engine** that learns from the metadata of each movie rather than user ratings or reviews.  

By analyzing textual data from movie attributes, the model computes similarity scores between films and provides the top recommended movies that match the input title.  
It demonstrates the fundamental working principle behind recommendation systems used by platforms such as **Netflix**, **Amazon Prime Video**, and **Disney+**.

---

## 💡 Main Ideas Behind the Project

- **Content-Based Filtering:**  
  The system relies solely on movie information such as genres, keywords, and overviews to find relationships between films.

- **Text Vectorization using CountVectorizer:**  
  Converts movie metadata into numerical vectors that represent the significance of each word.

- **Cosine Similarity for Recommendations:**  
  Measures how closely two movies are related based on their vector representation.

- **Feature Engineering:**  
  Combines important textual features like `overview`, `genre`, `keywords`, and `cast` into a single column (`tags`) to capture movie essence.

- **Scalability:**  
  Works effectively on large datasets (10,000+ movies) with optimized vectorization and similarity computation.

---

## 🧩 Steps Involved in the Project

1. **Data Collection & Loading:**  
   Loaded a dataset containing 10,000 movies and 9 key features — `id`, `title`, `genre`, `original_language`, `overview`, `popularity`, `release_date`, `keywords`, and `cast`.

2. **Data Cleaning & Preprocessing:**  
   Handled missing values, formatted text data, and combined relevant columns into one feature-rich textual column.

3. **Text Representation:**  
   Applied **CountVectorizer** to convert textual movie information into vectors for machine interpretation.

4. **Similarity Computation:**  
   Calculated cosine similarity scores between all movies to measure how close their descriptions are.

5. **Recommendation Generation:**  
   Based on the similarity matrix, the system identifies and lists the top similar movies for any selected title.

6. **Evaluation & Visualization:**  
   Performed exploratory data analysis (EDA) to visualize genre distributions, language counts, and popularity metrics.

---

## ⚙️ Tech Stack Used

| Category | Tools / Libraries |
|-----------|------------------|
| **Programming Language** | Python |
| **Data Analysis** | Pandas, NumPy |
| **Machine Learning / NLP** | Scikit-learn (CountVectorizer, Cosine Similarity) |
| **Visualization** | Matplotlib, Seaborn |
| **Environment** | Jupyter Notebook |
| **Version Control** | Git & GitHub |

---

## 🌟 Key Features

- Works on pure content-based similarity — no dependency on user ratings.  
- Processes and compares 10,000+ movies efficiently.  
- Scalable and extendable for web or app integration.  
- Provides accurate and intuitive recommendations based on real-world movie data.  
- Can be enhanced with APIs like TMDB for posters, ratings, and live data.

---

## 👨‍💻 Developed By

**🧑‍💻 Sauvir Wodehra**  
🎓 *B.Tech in Computer Science and Engineering, IIIT Kota (2023–2027)*  
💡 Enthusiastic about **Backend Development**, **Machine Learning**, and **Data-Driven Systems**.  
🚀 Passionate about building intelligent software that merges data science and real-world applications.

**📬 Email:** [sauvirwodehras3136@gmail.com](mailto:sauvirwodehras3136@gmail.com)  
**🌐 GitHub:** [https://github.com/SauvirWodehra](https://github.com/SauvirWodehra)  
**💼 LinkedIn:** [https://www.linkedin.com/in/sauvir-wodehra-032821257/](https://www.linkedin.com/in/sauvir-wodehra-032821257/)  
**🏫 Institute:** Indian Institute of Information Technology, Kota  
**🌍 Location:** Amritsar, Punjab, India  

---

⭐ *“Turning data into meaningful insights and intelligent recommendations.”*
