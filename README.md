# Anime Recommendation System🎌

[![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)](https://www.python.org/)
![Pandas](https://img.shields.io/badge/-Pandas-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?logo=numpy&logoColor=white)
![Plotly](https://img.shields.io/badge/-Plotly-3F4F75?logo=plotly&logoColor=white)
[![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/)
[![Keras Tuner](https://img.shields.io/badge/-Keras%20Tuner-FF6F00?logo=keras&logoColor=white)](https://keras-team.github.io/keras-tuner/)
[![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Kaggle](https://img.shields.io/badge/-Kaggle-blue?logo=kaggle)](https://www.kaggle.com/)
![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?logo=jupyter&logoColor=white)


## Overview 🌟📚

Welcome to the Anime Recommendation System! This project aims to provide personalized anime recommendations based on collaborative filtering techniques.

The application utilizes user-based collaborative filtering to find similar users based on their anime preferences and recommends animes liked by similar users that the target user has not watched yet. Additionally, the system employs item-based collaborative filtering to find similar animes based on their features (e.g., genres, synopsis) and recommends animes similar to the one provided by the user.

The dataset used for training and recommendation includes various anime titles, user ratings, and anime features such as genres and synopses. The model was trained using TensorFlow and Keras to create anime embeddings for both users and animes, facilitating efficient similarity comparisons.


Due to the large size of the model file i.e `myanimeweights.h5`, it cannot be directly hosted on GitHub. However, you can still access and download the files from my [Google Drive](https://drive.google.com/file/d/1dypdLwProMGxy7h8hi49a-kHiu_nFz1U/view?usp=sharing).

## About the Dataset

The dataset used in the Anime Recommendation System project offers a wealth of valuable information, encompassing anime characteristics, ratings, popularity, viewership, user behavior, and preferences. It serves as a comprehensive resource for conducting diverse analyses, such as identifying top-rated anime, exploring popular genres, and gaining insights into viewer trends. With this dataset, personalized recommendation systems can be developed, user behavior can be analyzed, and clustering can be employed to understand anime trends and user preferences. Additionally, the dataset enables examination of user interactions, ratings, and engagement with anime, providing essential inputs for collaborative filtering and similarity analysis.


🎬 As an anime weeb, I have always been captivated by the fascinating world of anime. The colorful characters, gripping storylines, and imaginative worlds never fail to spark my imagination and evoke a sense of wonder. It didn't take long for me to realize that the joy I experienced while watching animes could be elevated to another level by bringing the magic of anime recommendations into real life. The idea of creating an Anime Recommendation System took root in my mind, and I embarked on this exciting journey to develop a platform that could intelligently suggest animes based on individual preferences. This project allowed me to combine my passion for anime with the fascinating realm of data science and machine learning, enabling me to create a personalized anime discovery experience for myself and fellow anime enthusiasts. Join me as I unravel the world of anime recommendations and witness the magic of data-driven suggestions that open up new horizons in the anime universe! 🎬


## Installation

This project is written in Python 3.11.4. If you don't have Python installed, you can download it from the [official website](https://www.python.org/downloads/). If you have an older version of Python, you can upgrade it using the pip package manager, which should be already installed if you have Python 2 >=2.7.9 or Python 3 >=3.4 on your system.
To install the required packages and libraries, you can use pip and the provided requirements.txt file. First, clone this repository to your local 


```

Once you have cloned the repository, navigate to the project directory and run the following command in your terminal or command prompt:

```bash
pip install -r requirements.txt
```

This will install all the necessary packages and libraries needed to run the project.

If you prefer, you can also create a virtual environment to manage the project dependencies separately. This helps in isolating the project's environment from the system-wide Python installation.

## Directory Tree

```
|   .gitignore
|   app.py
|   LICENSE.md
|   package-lock.json
|   package.json
|   README.md
|   requirements.txt
|
+---model
|       anime-dataset-2023.pkl
|       anime_encoder.pkl
|       myanimeweights.h5
|       users-score-2023.csv
|       user_encoder.pkl
|
+---notebooks
|       anime-recommendation-1.ipynb
|       anime-recommendation-2.ipynb
|
+---resource
|       anime.mp4
|
+---static
|       main.css
|       style.css
|
\---templates
        index.html
        recommendations.html
