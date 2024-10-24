# NLP-Model-for-Medical-Question-Answering
This repository contains a project focused on **Natural Language Processing (NLP)** applied to **medical question-answering**. The project leverages advanced language models such as **Llama-2**, **Mistral**, and **Word2Vec**, among others, to provide accurate answers to medical questions by fine-tuning models on custom datasets.

## Features
- **Data Preprocessing**:
  - Removes duplicates, digits, and punctuation from the dataset.
  - Term frequency analysis and visualizations.
  - Word embeddings using **Word2Vec** and **Glove** for identifying similar terms.
  
- **Topic Modeling and Clustering**:
  - Clustering of answers using **KMeans** and **Latent Dirichlet Allocation (LDA)**.
  - Dimensionality reduction with **t-SNE** for 3D visualization of topics.

- **Model Training**:
  - Fine-tuning of state-of-the-art models including **Llama-2** and **Mistral-7B** for generating medical answers.
  - Parameter-efficient fine-tuning (PEFT) with **Low-Rank Adaptation (LoRA)**.
  - Hugging Face integration for seamless model uploading and sharing.

- **Evaluation**:
  - F1 score evaluation of model outputs against reference answers.
  - Cross-encoder models used for semantic search and answer retrieval.

- **Semantic Search**:
  - **SentenceTransformer** models for embedding questions and answers.
  - ANN-based search with **HNSWLIB** for efficient retrieval of relevant answers from the dataset.

## Project Structure
- `nlp_ge_benedetto_sarrocco_pachioli.py`: Main Python script with functions for data cleaning, model training, semantic search, and evaluation.
- `results/`: Directory where the training logs and model outputs are saved.

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/nlp-medical-qa.git
   cd nlp-medical-qa
   ```

## License
This project is licensed under the MIT License.

---

Feel free to customize this as per your preferences or add any additional sections based on your specific needs.
