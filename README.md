# Personalized Book Recommendation System

## 📌 Project Overview
This project is a **Personalized Book Recommendation System** designed to provide users with book suggestions based on historical data and content similarity. It utilizes **cosine similarity** to find books similar to a given input and offers an interactive user interface built with **Streamlit**.

## 🚀 Features
- 📚 **Book Recommendations**: Suggests books based on similarity analysis.
- 🖥 **Interactive Web Interface**: Built using Streamlit for an intuitive user experience.
- 📊 **Data Processing**: Cleans and processes book data obtained from Kaggle.
- 🔍 **Similarity Calculation**: Uses **Cosine Similarity**.
- 💾 **Model Storage**: Saves trained models using the **pickle** library.

## 🛠️ Tech Stack
- **Frontend**: Streamlit
- **Backend**: Python (Jupyter Notebook)
- **Libraries Used**: Pandas, Scikit-learn, Numpy, Pickle
- **Dataset**: Kaggle Book Dataset


## 🔧 Installation & Setup
### Prerequisites
Ensure you have **Python 3.1** installed along with the required dependencies.

### Steps to Run the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/SandharbhGupta/Read-Next.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```sh
   streamlit run app.py
   ```
4. Enter a book name in the input field and get recommendations!

## 📊 How It Works
1. Loads the **Kaggle book dataset** and processes it.
2. Converts book descriptions into **TF-IDF vectors**.
3. Computes **cosine similarity** to find similar books.
4. Displays recommendations through the **Streamlit web interface**.

## 📌 Future Enhancements
- 🔄 **Collaborative Filtering** to enhance recommendations.
- 📝 **User Feedback System** to improve results dynamically.
- 🛠️ **Deploy as a Web App** for global accessibility.

Live link:- https://read-next-3tyevzjvosdm4fjxnp7upj.streamlit.app/
