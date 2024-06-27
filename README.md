# RAG_assisted_research

## Project Overview

This project develops a pipeline to transform academic manuscripts into a searchable vector database, enabling efficient querying based on content relevance. The process involves several key stages, from raw manuscript handling to deep learning-based text retrieval.

## Pipeline Steps

### Manuscript Collection:

Gather all manuscripts of interest and store them as PDFs in a specified folder.

### Text Partitioning:

Use unstructured.io to partition the PDF documents into text segments.
Save the partitioned text files to a targeted folder for further processing.

### Text Embedding:

Choose an appropriate embedding algorithm to convert text data into vector representations.
Embed the partitioned files into a vector database, which is subsequently stored in a designated folder.

### Query Model Setup:

Select a large language model to develop a retrieval strategy. This model will facilitate querying the vector database to retrieve relevant document sections based on input questions or prompts.

### Question Answering:

Utilize the built retrieval strategy and the large language model to answer queries. This allows users to extract information directly from the embedded vector database effectively.

## Current Status

The pipeline is operational, but ongoing adjustments and optimizations are being made to enhance performance and accuracy.

## Future Work

Continue to refine the embedding and retrieval processes to improve response times and accuracy.
Expand the document dataset and potentially integrate more diverse data sources.
Explore advanced NLP features and customization options for specific research needs.
