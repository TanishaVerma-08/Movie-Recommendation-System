# 🎬️ Movie Recommendation System

This project is an AI/ML-based movie recommendation system that suggests movies similar to a user-specified movie title. It utilizes natural language processing techniques and machine learning algorithms to provide recommendations.

## 📋 Project Overview

The primary objectives of this project are:

- To develop a system that recommends movies based on user input.
- To implement natural language processing techniques to analyze movie data.
- To apply machine learning algorithms to find similarities between movies.

## 🛠️ Features

- **Movie Recommendation**: Suggests movies similar to the one provided by the user.
- **Data Processing**: Utilizes CountVectorizer to transform text data into feature vectors.
- **Similarity Calculation**: Employs cosine similarity to measure the similarity between movies.

## 🗂️ Project Structure

```
Movie-Recommendation-System/
├── Movie_Recommendation_System.ipynb  # Jupyter Notebook with implementation
├── movies.csv                         # Dataset containing movie information
└── README.md                          # Project documentation
```

## 🔧 Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/TanishaVerma-08/Movie-Recommendation-System.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd Movie-Recommendation-System
   ```

3. **Install the required packages**:

   Ensure you have Python and Jupyter Notebook installed. Then, install the necessary libraries:

   ```bash
   pip install pandas scikit-learn
   ```

## 🚀 Usage

1. **Open the Jupyter Notebook**:

   Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

   Then, open the `Movie_Recommendation_System.ipynb` file.

2. **Run the Notebook**:

   Execute the cells in the notebook to load the data, process it, and generate movie recommendations based on user input.

## 📝 Dataset

The `movies.csv` file contains the dataset used for this project. Ensure this file is present in the project directory before running the notebook.
