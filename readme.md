📚 Book Recommendation System

A machine learning based book recommendation system that suggests books to users based on similarity and popularity.

The system uses collaborative filtering and cosine similarity to recommend books that are most relevant to a given title.
A simple Flask web interface is provided to interact with the recommender.

🚀 Features

Popular book recommendations

Similar book suggestions

Fast recommendations using precomputed similarity matrix

Web interface built with Flask

Lightweight and easy to run locally

🧠 Technologies Used

Python

Pandas

NumPy

Scikit-learn

Flask

Pickle (model serialization)

Cosine Similarity

📂 Project Structure
'''

RECOMMENDER_SYSTEM/
│
├── Model/                     # trained model files (if any)
├── templates/                 # HTML templates for Flask UI
├── app.py                     # main Flask application
├── book_recc_system.ipynb     # model development notebook
├── books.pkl                  # processed book data
├── popular.pkl                # popular books data
├── similarity_scores.pkl      # similarity matrix
└── README.md

'''

⚙️ Setup Instructions
1️⃣ Clone the repository
git clone https://github.com/your-username/book-recommendation-system.git
cd book-recommendation-system
2️⃣ Install dependencies
pip install -r requirements.txt
3️⃣ Run the application
python app.py

Open browser and go to:

http://127.0.0.1:5000
📊 Dataset

CSV dataset files are not included in this repository due to size constraints.

The project uses a book rating dataset containing:

Users

Books

Ratings

If needed, you can use any standard book recommendation dataset such as the Book-Crossing dataset or similar.

🧩 How It Works

User-book rating matrix is created

Cosine similarity is computed between books

Most similar books are retrieved for recommendations

Flask app displays results in a web interface