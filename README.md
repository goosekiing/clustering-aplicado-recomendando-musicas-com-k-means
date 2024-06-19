# Clustering Applied: Recommending Songs with K-Means

This repository contains a project focused on using clustering techniques to recommend songs based on their audio features. The dataset includes 20,311 tracks released between the years 2000 and 2020. The data are evaluated and verified to be suitable for a machine learning model. A pipeline is created to scale the data and reduce dimensionality to two dimensions. KMeans is then used to cluster the tracks. Euclidean distance is used to find the "closest" songs to a selected song within a cluster. The album images of these recommended songs are retrieved using the Spotipy library to provide a graphical representation of the 10 recommended songs similar to the chosen one.

## Project Overview
The goal of this project is to develop a music recommendation system using K-Means clustering and integrate it with the Spotify API to fetch album images of recommended tracks.

## Course Details
This project was completed as part of the Machine Learning course on Alura. For more information about the course, visit [Alura](https://cursos.alura.com.br/formacao-machine-learning-v64177).

## Objectives Achieved
- Understand how music recommendation systems work.
- Learn and use unsupervised machine learning methods for music classification.
- Identify the criteria and features of songs used for recommendations.
- Create a music recommender and connect it with the Spotify API.
- Gain in-depth knowledge of the Spotify API using the Spotipy library.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Spotipy

## Project Structure
The directory structure of the project is as follows:
```
clustering-aplicado-recomendando-músicas-com-k-means/
│   .env
│   .gitignore
│   project-1.ipynb
│   README.md
└───Dados
        Dados_totais.csv
        data_by_genres.csv
        data_by_year.csv
```

## Environment Variables
The `.env` file is not available in the GitHub repository. It contains the variables `CLIENT_ID` and `CLIENT_SECRET`, which are retrieved in the code using `str(os.getenv("VARIABLE"))`. These keys are personal, and Spotify users can obtain their own keys using Spotify for Developers (available at: https://developer.spotify.com/).

## How to Run the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/goosekiing/clustering-aplicado-recomendando-músicas-com-k-means.git
   ```
2. Navigate to the project directory:
   ```sh
   cd clustering-aplicado-recomendando-músicas-com-k-means
   ```
3. Create a `.env` file with your Spotify API `CLIENT_ID` and `CLIENT_SECRET`.
4. Open the Jupyter Notebook:
   ```sh
   jupyter notebook project-1.ipynb
   ```

## Learn More
To learn more about clustering techniques and machine learning, visit the [course page on Alura](https://cursos.alura.com.br/formacao-machine-learning-v64177).

Feel free to explore, modify, and use this project as a foundation for your own machine learning projects!

## Language
The language used in this project is Brazilian Portuguese (pt-br).
