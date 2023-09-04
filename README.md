# LungCancerModules

## Step 1: Pre-processing
- Run preprocessing.ipynb using input.tsv to produce the required pre-processed data (input_preprocessed.xlsx)

## Step 2: Network Construction
- Run network.ipynb using input_preprocessed.xlsx to construct the graph (gene_gene_interaction_graph.graphml)

## Step 3: Clustering
- Run clustering.ipynb using gene_gene_interaction_graph.graphml to produce the final clusters (optimal_clusters_sorted.xlsx)


### NOTE: some parts of the code might take longer (1-2 hours) to run
