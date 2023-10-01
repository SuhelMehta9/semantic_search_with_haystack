# semantic_search_with_haystack

This repository contains code for performing semantic search using `sentence-transformers/multi-qa-MiniLM-L6-cos-v1` and `EmbeddingRetriever`.

To use this code, you will need to install the following Python packages:
```bash
pip install qdrant-haystack
pip install farm-haystack[inference]
```

To run the code, simply open the ipynb file in jupyter notebook or jupyter lab and run each cell.

This will search the Qdrant for documents that are similar to the query and return the results.

To learn more about how to use this code or about semantic search, please read this blog [Semantic Search Using Haystack](https://suhelmehta9.github.io/2023/09/30/semantic-search-using-haystack.html).
