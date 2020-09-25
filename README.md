# clustering_happy_moments

### Structure

    .
    ├── visualisations 
        ├── clustering # Contains results from Clustering for different input feature versions (TF-IDF, enriched TF-IDF, Word Embeddings) and for every dataset (datatype: .png). For examples presented in submitted paper, .csv-files with cluster attributions are added.
        ├── dataexploration # Contains dataexploration for all datasets.
    ├── scripts
        ├── d2v.model   # Doc2Vec-Model trained on HappyDB data.
        ├── dataexploration.ipynb   # Script to explore datasets.
        ├── doc2vec.ipynb   # Script to prepare, calculate and evaluate word embeddings.
        ├── pipeline_clustering.ipynb   # Script to calculate clusterings through a pipeline.
        ├── preprocessing.ipynb # Script to preprocess data.
    ├── utils # Contains Jupyter Notebooks and scripts to visualize datasets and results and to support data processing.
    └── README.md
