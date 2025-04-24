# Movie Recommendation Engine

## DataSet Links

## Original DataSets
The Movies Dataset:  [Movies Dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset)

Streaming platform Dataset: [Streaming Platfrom](https://www.kaggle.com/datasets/ruchi798/movies-on-netflix-prime-video-hulu-and-disney)

Top 1000 Highest grossing Movies: [Top 1000 Highest grossing Movies](https://www.kaggle.com/datasets/therealoise/top-1000-highest-grossing-movies-of-all-time)

## Dataset used for Milestone 2 and Milestone 3

Google Drive Link: [Milestone 2 Data](https://drive.google.com/file/d/1NT8PZlmp0_6VgyWUPH-kxBVXxSUC67W0/view?usp=sharing)

Google Drive link: [Milestone 3 Data](https://drive.google.com/file/d/1Vm21gfRIXYydj32FUuNcMCg8Ii1D9_HP/view?usp=sharing)

## Jupyter NoteBook and Demo Links

 [MileStone 1 Notebook](https://www.kaggle.com/code/ashfaaqahmed/ids-milestone-1/notebook)

The above hyperlink links to the Jupyter notebook that was used for the analysis. The notebook can be run from kaggle to visualize the EDA analysis on the data and reproduce the findings of the milestone1 report.

[MileStone 2 Notebook](https://www.kaggle.com/code/ashfaaqahmed/ids-milestone-2-notebook)

The above hyperlink links to the Jupyter notebook that was used as part of the milestone2, I extended the original notebook that was used for the EDA analysis and Data preprocessing for milestone 1. 

Please refer to the Section titled **MileStone 2** in the Notebook

[MileStone 3 Notebook](https://www.kaggle.com/code/ashfaaqahmed/ids-milestone-3-notebook)

The above hyperlink links to the Jupyter notebook that was used as part of the milestone3, I extended the original notebook that was used for the Feature selction, Feature Engineering and Model selection performed in Milestone 2. 

Please refer to the Section titled **MileStone 3** in the Notebook

Please find the links below for Milestone 3 submissions.

- [Milestone 1 and Milestone 2 Summary presentation](https://docs.google.com/presentation/d/1VGi9z02sN7jCBhPt5kYKT8qPaokWKHK2/edit?usp=sharing&ouid=107751061587945509251&rtpof=true&sd=true)

- [Milestone 3 submission Video - 1](https://drive.google.com/file/d/14n_OF8vub0C9RGSN54OgECv62BPLmvoI/view?usp=sharing)

- [Milestone 3 submission - Tool Demo](https://drive.google.com/file/d/1zoLzZ3_aNJelmKoYYJIttHrFx4pBrUKJ/view?usp=sharing)

**Note**: The Notebooks has been enabled for public viewing for the prupose of this project.

# Movie Recommendation Engine Streamlit

This is an interactive Streamlit app that recommends movies based on user input. It supports clustering-based approaches as well as FastText-based semantic similarity.

## Features

- Select a movie from a 3x3 grid of recent popular titles.
- Choose a recommendation model:
  - K-Means
  - DBSCAN
  - Gaussian Mixture Model (GMM)
  - FastText (text similarity)
- Visualize recommendations and cluster positions using PCA.


## How to Run Locally

1. Clone the repository:
    ```bash
    git clone https://github.com/Ashfaq-Ahmed-Mohammed/cap5771sp25-project.git
    cd Scripts
    ```

2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the app:
    ```bash
    streamlit run main.py
    ```

## Streamlit Cloud

You can run this app directly in your browser via Streamlit Cloud without installing anything.

Link: https://mainpy-xfgck8om3dmndpyt8rbppe.streamlit.app/

## Models

| Model       | Description                           |
|-------------|---------------------------------------|
| KMeans      | Clustering based on numeric features  |
| DBSCAN      | Density-based clustering              |
| GMM         | Probabilistic soft clustering         |
| FastText    | Cosine similarity on text embeddings  |

## Dependencies

- streamlit
- pandas
- numpy
- scikit-learn
- matplotlib

See `requirements.txt` for pinned versions.

## Links to reports from Milestones

- [Milestone 1 report](https://github.com/Ashfaq-Ahmed-Mohammed/cap5771sp25-project/blob/main/Report/Milestone1.pdf)
- [Milestone 2 report](https://github.com/Ashfaq-Ahmed-Mohammed/cap5771sp25-project/blob/main/Report/Milestone2.pdf)
- [Milestone 3 report](https://github.com/Ashfaq-Ahmed-Mohammed/cap5771sp25-project/blob/main/Report/Milestone3.pdf)




