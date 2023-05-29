# Reddit Hyperlinks Analysis

This repository contains the code and analysis for exploring the soc-RedditHyperlinks dataset. The analysis focuses on Link Analysis, PageRank, and Hubs and Authority algorithms.

## Dataset

The chosen dataset for this analysis is the soc-RedditHyperlinks dataset. It represents hyperlinks between two subreddits (communities on Reddit) and contains information such as timestamps, sentiment, and text property vectors. The dataset spans 2.5 years from January 2014 to April 2017.

## Link Analysis

The analysis of the network provides insights into the structure and characteristics of the Reddit hyperlinks network.

1. Number of Nodes: 35,776
2. Number of Edges: 137,821
3. Average In-degree: 3.852
4. Average Out-Degree: 3.852
5. Node with Max In-degree: 'askreddit' (In-degree: 2,161)
6. Node with Max Out-degree: 'subredditdrama' (Out-degree: 1,350)
7. Density of the Network: 0.00011

### Degree Distribution Plot

The degree distribution of the network is plotted, showing the in-degree and out-degree separately.

### Local Clustering Coefficient (LCC)

The LCC is a measure of the degree to which nodes in a graph tend to cluster together. In this analysis, both the in-nodes and out-nodes LCCs are calculated separately. The unweighted LCC is the average of the in-nodes and out-nodes LCCs, while the weighted LCC takes into account the number of nodes in each category.

## PageRank, Hubs, and Authority

PageRank, Authority, and Hub scores are calculated for each node in the network.

1. PageRank Scores: The PageRank algorithm measures the importance of nodes based on the structure of incoming links.
2. Authority and Hub Scores: The Authority score represents the importance of nodes based on incoming links, while the Hub score represents the importance based on outgoing links.

### Comparison between PageRank, Authority, and Hub Scores

The correlation between the PageRank score and Authority score is 0.44667468261192805.

The correlation between the PageRank score and Hub score is 0.8485383243837176.

The correlation between the Authority score and Hub score is 0.5551260436796563.

## Code

The code for this analysis can be found in the respective directories. The code is implemented using Python and relies on libraries such as pandas and matplotlib for data processing and visualization.

Please refer to the individual code files for a detailed understanding of the implementations.
