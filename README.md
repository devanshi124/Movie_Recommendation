#  Movie Recommendation System

A scalable **Content-Based Movie Recommendation System** built using **Machine Learning (TF-IDF + Cosine Similarity)** and deployed via **FastAPI** with an interactive frontend interface.

This project demonstrates practical implementation of NLP-driven recommendation systems and end-to-end ML deployment.



##  Project Highlights

-  Built a content-based recommender using advanced **text feature engineering**
-  Implemented **TF-IDF vectorization** for numerical text representation
-  Applied **Cosine Similarity** for similarity ranking
-  Designed RESTful APIs using **FastAPI**
-  Integrated dynamic movie posters using **TMDB API**
-  Structured project for scalable backend deployment
-  Developed interactive frontend interface



##  Technical Approach

### 1️. Feature Engineering
- Combined movie metadata: **genres, overview, keywords, and cast**
- Created a unified textual feature column

### 2️. Vectorization
- Used **TF-IDF (Term Frequency – Inverse Document Frequency)**
- Converted textual data into high-dimensional numerical vectors

### 3️. Similarity Computation
- Generated **Cosine Similarity matrix**
- Ranked movies based on similarity score
- Returned Top-N most relevant recommendations



##  Tech Stack

- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **FastAPI**
- **Uvicorn**
- **Streamlit**
- **TMDB API**



##  Project Structure

```
Movie_Recommendation/
│
├── app.py              # Streamlit frontend
├── main.py             # FastAPI backend
├── data/               # Dataset files
├── model/              # Saved models (if applicable)
├── requirements.txt
└── README.md
```



##  Installation & Setup

### 1️. Clone the Repository

```bash
git clone https://github.com/devanshi124/Movie_Recommendation.git
cd Movie_Recommendation
```

### 2️. Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate
```

### 3️. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️. Run FastAPI Backend

```bash
uvicorn main:app --reload
```

### 5️. Run Frontend (Streamlit)

```bash
streamlit run app.py
```

---





##  Learning Outcomes

- Real-world implementation of **NLP-based recommender systems**
- Deep understanding of **TF-IDF mathematics & vector space models**
- REST API design using **FastAPI**
- Backend-frontend integration
- Structuring ML projects for production environments



##  Future Enhancements

- Hybrid recommendation system (Content + Collaborative Filtering)
- Dimensionality reduction using **SVD**
- User-based personalization
- Cloud deployment (AWS / Render)
- Docker containerization

---


