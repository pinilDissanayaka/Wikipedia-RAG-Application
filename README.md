# Wikipedia-RAG-Application

This repository contains a Retrieval-Augmented Generation (RAG) application utilizing the Pinecone vector store and the Gemma 2 9B large language model. This application allows users to input Wikipedia links and ask questions about the content. The system employs a hybrid search technique to provide accurate and relevant answers.

## Features
- Hybrid Search Technique: Combines the strengths of both keyword-based and vector-based search methods to retrieve the most relevant information.
- Pinecone Vector Store: Efficiently stores and retrieves vector representations of Wikipedia content.
- Gemma 2 9B LLM: Generates human-like responses based on the retrieved information.
- User-Friendly Interface: Simple and intuitive interface for adding Wikipedia links and asking questions.

## Installation
1. Clone the repository:
```
git clone https://github.com/pinilDissanayaka/Wikipedia-RAG-Application.git
cd Wikipedia-RAG-Application
```

2. Create and activate a virtual environment:
```
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install the required packages:
```
pip install -r requirements.txt
```

## License
This project is licensed under the MIT License - see the LICENSE file for details.
