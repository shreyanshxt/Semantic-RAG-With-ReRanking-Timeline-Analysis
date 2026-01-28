# Semantic RAG with Re-Ranking and Timeline Analysis

A Jupyter Notebook implementation of a Retrieval-Augmented Generation (RAG) system incorporating semantic search, re-ranking, and timeline analysis.

## Description

This project demonstrates a RAG pipeline that goes beyond simple vector retrieval. It includes:
- **Semantic Search**: Using vector embeddings to find relevant content.
- **Re-Ranking**: Refining search results for better accuracy.
- **Timeline Analysis**: Extracting and analyzing temporal information from the retrieved context.

The core logic is contained within the `DosOs_Final_Code.ipynb` notebook.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/shreyanshxt/Semantic-RAG-With-ReRanking-Timeline-Analysis.git
   cd Semantic-RAG-With-ReRanking-Timeline-Analysis
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Open `DosOs_Final_Code.ipynb` and run the cells.

## Dependencies

- `faiss-cpu`
- `numpy`
- `pandas`
- `sentence-transformers`
- `torch`
- `transformers`
