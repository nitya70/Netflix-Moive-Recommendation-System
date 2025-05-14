
# 🎬 Netflix Movie Recommendation System

This project is a content-based recommendation engine built using Python. It helps users discover Netflix movies and shows based on their preferences or search inputs. It uses similarity metrics and metadata to recommend relevant titles.

## 🔍 Features

- Content-based filtering using cosine similarity
- Real-time movie recommendations
- Clean and interactive web interface (via Streamlit or Flask)
- Utilizes Netflix's movie metadata

## 📁 Project Structure

Netflix-Movie-Recommendation-System/
├── app.py # Main application (Streamlit/Flask)

├── Netflix_Recommendation_Engine.ipynb # Notebook with recommendation logic

├── netflix_titles.csv # Raw dataset from Netflix

├── movies_df.csv # Preprocessed metadata

├── README.md # Project documentation

└── LICENSE # MIT License



## 🛠️ Tech Stack

- Python 3
- Pandas, NumPy
- Scikit-learn
- Streamlit or Flask (for frontend)
- Cosine Similarity (from sklearn)

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Netflix-Movie-Recommendation-System.git
cd Netflix-Movie-Recommendation-System


2. Install Requirements
bash
Copy
Edit
pip install -r requirements.txt
(Create requirements.txt if not present)

Example contents:

txt
Copy
Edit
pandas
numpy
scikit-learn
streamlit
3. Run the App
bash
Copy
Edit
streamlit run app.py


💡 How It Works
Data Loading: Reads movie metadata from movies_df.csv.

Text Vectorization: Converts movie descriptions and tags into vectors.

Similarity Matching: Calculates cosine similarity between movies.

Recommendation: Displays top N similar movies based on input.

📊 Sample Dataset
Source: Netflix Movies Dataset

Columns: title, director, cast, genre, description, release_year, etc.

🧪 Example
Type: Inception
Output: Shows a list of similar titles available on Netflix.
