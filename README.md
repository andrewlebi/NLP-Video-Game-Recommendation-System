# Video Game Recommendation System

## Introduction
This Video Game Recommendation System leverages Natural Language Processing (NLP) techniques to provide personalized game recommendations based on a given video game. It meticulously processes and analyzes video game data from a June 2023 dataset consisting of 60,000 rows, employing a variety of Python libraries for data cleaning, visualization, and machine learning/NLP techniques to identify and recommend games similar to user favorites. Test cases demonstrating the usage of the recommendation system are also provided in the last section of the Jupyter Notebook.

## Features
- **Data Processing and Cleaning:** Prepares video game data for analysis by focusing on relevant features.
- **Exploratory Data Analysis (EDA):** Utilizes different data visualization techniques to uncover insights and trends within the video game industry.
- **NLP-based Recommendation:** Employs TF-IDF vectorization with scikit-learn to generate recommendations based on textual descriptions of games.
- **Natural Language Processing:** Utilizes NLTK alongside scikit-learn for preprocessing text data, enabling efficient analysis and similarity computation between different video game descriptions to find matches that align with user preferences.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- scikit-learn
- NLTK

## How It Works
1. **Data Preparation:** The code cleans and formats video game data for analysis using Pandas and NumPy, ensuring it is suitable for NLP and machine learning techniques.
2. **Analysis and Visualization:** Performs EDA with Matplotlib, Seaborn, and Plotly to gain a deeper understanding of the video game industry's trends and the amount of video games released over time.
3. **Recommendation Generation:** Uses NLTK for text preprocessing and scikit-learn's TF-IDF vectorization to analyze game descriptions, compare their similarity, and recommend titles similar to those the user likes.

## Contributing
Contributions to enhance the project's capabilities and efficiency are welcome. Please feel free to submit issues, fork the repository, and submit pull requests.

## License
This project is under the MIT License. See the LICENSE file for details.

## Acknowledgments
- The data used in this project comes from the following Kaggle dataset: https://www.kaggle.com/datasets/arnabchaki/popular-video-games-1980-2023/data.
