# Working with Graph Data 🌧️
In this folder, I have tried to work with graphs. I converted sentences to graphs and also used some parsing techniues. Additionally, worked with embedded data to perform a very efficient `Faiss` search.

#### Sentence to Parsed Tree

Creating a Parsed tree of a sentence using **`stanford parser`**.

  `parse_tree.draw()
  `
#### Tree to Graph

By performing a breadth first search within a tree, converting the tree to a graph. **`Networkx`** library has been used for the graph visualization.
#### Faiss Search on Embedded Graph Data

Searching similar sentences from graph embedded data using **`Faiss`**. The dimension has been set to 300. I find top 10 sentences that are similar to the given sentence. This search return the index number of the similar embedded graph data.

Faiss is developed by **Facebook AI Research**. It is basically used for similarity search and clustering of dense vectors. More on **Faiss** can be found [here](https://github.com/facebookresearch/faiss).

How to covert a graph to embedded data is not the purpose of this code and the embedded data has also not been shared due to confidentiality.

