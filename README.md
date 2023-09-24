# GPT-2 Semantic Search

A simple semantic search example using OpenAI's GPT-2 model to find the most relevant documents to a given query. This project demonstrates how to create document embeddings and calculate cosine similarity to rank documents based on their similarity to the query.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Semantic search is a powerful technique for finding relevant documents based on their meaning rather than just keywords. In this project, we leverage OpenAI's GPT-2 model to create document embeddings for a set of documents and then calculate the cosine similarity between a query and the documents to rank them by relevance.

The example provided uses a small set of documents and a query related to smartphone specifications. You can adapt this code to your specific use case with different documents and queries.

## Installation

Before running the code, you need to install the required libraries:

```bash
pip install transformers
pip install torch
pip install scikit-learn
```

## Usage

1. Clone this repository to your local machine.

2. Open the Jupyter Notebook or Python script provided in this repository.

3. Customize the `documents` list with your own set of documents and update the `query` variable with your query.

4. Run the code to see the search results, which will display documents ranked by their similarity to the query.

5. Experiment with different queries and document sets to explore the capabilities of semantic search with GPT-2.

```python
# Example query and documents
documents = [
    "Introducing our flagship smartphone, the XYZ Model X.",
    "This cutting-edge device is designed to redefine your mobile experience.",
    "With a 108MP camera, it captures stunning photos and videos in any lighting condition.",
    "The AI-powered processor ensures smooth multitasking and gaming performance.",
    "The large AMOLED display delivers vibrant visuals, and the 5G connectivity offers blazing-fast internet speeds.",
    "Experience the future of mobile technology with the XYZ Model X.",
]

query = "Could you provide detailed specifications and user reviews for the XYZ Model X smartphone, including its camera features and performance?"
```

## Contributing

Contributions to this project are welcome! If you have ideas for improvements or new features, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
