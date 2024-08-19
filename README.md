# Multilingual Speech Recognition and Summarization Model

This project focuses on building a multilingual speech recognition and summarization model by integrating OpenAI's Whisper Large V3 model with Retrieval-Augmented Generation (RAG). The system is designed to take audio or video inputs, transcribe and summarize the content, store the results in a vector database using FAISS, and respond to user queries based on the stored content.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project enables real-time or batch processing of audio or video files for multilingual transcription and summarization. The system uses Whisper Large V3 for robust speech recognition across various languages and RAG for generating responses based on the stored information in a vector database.

### Key Components:
1. **Whisper Large V3**: A state-of-the-art speech recognition model that supports multilingual transcription.
2. **RAG (Retrieval-Augmented Generation)**: A model that retrieves relevant information from a database and generates responses to user queries.
3. **FAISS (Facebook AI Similarity Search)**: A vector database for storing and efficiently retrieving the transcribed and summarized content.

## Features

- **Multilingual Speech Recognition**: Supports multiple languages for transcription.
- **Summarization**: Generates concise summaries of transcribed content.
- **Vector Database Storage**: Stores transcriptions and summaries in a FAISS vector database for fast retrieval.
- **Query-based Response**: Responds to user queries using RAG by retrieving relevant information from the vector database.

## Installation

To set up this project locally, follow these steps:

### Prerequisites

- Python 3.8 or higher
- CUDA-compatible GPU for efficient processing (recommended)
- Install dependencies listed in `requirements.txt`

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/multilingual-speech-recognition-rag.git
   cd multilingual-speech-recognition-rag
2. **Create a virtual environment**:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
4. **Setup FAISS**:
   Ensure FAISS is installed and configured to work with your system. Follow the instructions provided in the          FAISS documentation.


## Usage
Follow the code given in the final_model.ipynb file.



## Model Architecture


### Whisper Large V3


1.**Purpose**:
   Transcription of multilingual speech.

2.**Features**:
   High accuracy across multiple languages.


### RAG (Retrieval-Augmented Generation)

1.**Purpose**:
   Generates responses by retrieving relevant content from the vector database.

2.**Features**:
   Combines the strengths of retrieval-based and generative models.


### FAISS Vector Database

1.**Purpose**:
   Stores transcriptions and summaries for efficient retrieval.

2.**Features**:
   Scalable and fast similarity search.


## Contributing 

We welcome contributions to improve the project. Please follow these steps:


Fork the repository.

Create a new branch (git checkout -b feature-branch).

Make your changes and commit them (git commit -m 'Add new feature').

Push to the branch (git push origin feature-branch).

Open a pull request.



## License

This project is licensed under Apache License 2.0. See the `LICENSE` file for more details.
