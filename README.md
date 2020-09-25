# clustering_happy_moments

HappyDB is a dataset that collects happy moments from people of all ages. In this project, different clustering algorithms are applied to the dataset in order to find patterns. The goal is to determine whether or not age and relationship status influence the type of moments that make people happy. The assumption is that younger, single persons tend to talk more about friendship and individual, momentary events whereas older, married participants find happiness in close personal relationships and achievements.

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
    └── README.md
