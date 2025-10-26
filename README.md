
📚 Book Recommendation System

📖 Overview

This project is a Book Recommendation System built using Python, NLP (Natural Language Processing), and Streamlit. It is designed to suggest books to users based on their interests by analyzing the content and descriptions of books. The recommendation engine uses TF-IDF (Term Frequency–Inverse Document Frequency) vectorization to convert book descriptions into numerical representations and calculates Cosine Similarity between them to find and recommend similar books.

The system is deployed as a Streamlit web application, providing users with a fast, interactive, and real-time recommendation experience. The user can enter or select a book title, and the app instantly returns a list of similar or recommended books based on content similarity.


---

🌟 Features

Built a content-based recommendation engine using NLP techniques.

Utilized TF-IDF Vectorization and Cosine Similarity for model logic.

Provides personalized book suggestions based on content similarity.

Implemented an interactive Streamlit web interface for real-time use.

Processes textual book descriptions to recommend related books.

Designed a clean and lightweight UI that runs locally or online.



---

🧩 Tech Stack

Language: Python

Libraries & Tools: Streamlit, Scikit-learn, Pandas, NumPy, Pickle

Algorithms Used: TF-IDF Vectorization, Cosine Similarity



---

🏗️ Project Structure

📂 Book-Recommendation-System
│
├── 📄 app.py                 # Streamlit web app file
├── 📄 BooksRecommender.ipynb # Jupyter notebook for data analysis & model building
├── 📄 model.pkl              # Trained model (TF-IDF/Cosine similarity)
├── 📄 book_names.pkl         # Serialized list of book titles
├── 📄 book_pivot.pkl         # Pivot data used for recommendations
├── 📄 final_rating.pkl       # Rating and popularity data
├── 📄 requirements.txt       # Required Python libraries
└── 📄 README.md              # Project documentation


---

⚙️ How to Run the Project

1️⃣ Clone the Repository

git clone https://github.com/<your-username>/Book-Recommendation-System.git
cd Book-Recommendation-System

2️⃣ Install Dependencies

pip install -r requirements.txt

3️⃣ Run the Streamlit App

streamlit run app.py

4️⃣ Use the Application
Once the Streamlit server starts, open the link displayed in your terminal.
Enter or select a book title — the system will display the top similar books based on content similarity.


---

🧾 requirements.txt

streamlit
pandas
numpy
scikit-learn
pickle-mixin


---

👨‍💻 Author

Priyanshu
B.Tech CSE (AI & ML) — Graphic Era Hill University, Bhimtal
📅 Project Duration: March 2025 – May 2025


---

🌟 Future Enhancements

Add hybrid recommendations combining user ratings and content similarity.

Integrate external APIs (Google Books or Goodreads) for live data.

Include user login and profile-based suggestions.

Deploy on a public cloud platform for easy access.



---

Would you like me to create a short GitHub “About” section for this repo too (like one-line summary + keyword tags: python, nlp, streamlit, recommender-system, etc.) so it looks perfect on your profile?
