# Legal-Assistance-System-for-Criminal-Violence-Victims-using-Natural-Language-Processing

## Overview
The "Legal Assistance System for Criminal Violence Victims" leverages Natural Language Processing (NLP) to provide legal guidance to individuals who are victims of criminal violence. Traditional legal processes can be confusing and inaccessible, often requiring victims to navigate complex legal terminology and procedures. This system is designed to simplify the process by allowing users to interact in natural language, making legal information more accessible and easier to understand.

## Functionality

### User Interaction: 
Victims can input their incidents in natural language, describing their experiences without needing to understand legal jargon.
### BERT-based NLP Processing: 
The system utilizes a fine-tuned BERT (Bidirectional Encoder Representations from Transformers) model to process user input, capturing contextual relationships and understanding the nuances of the language.
### Legal Guidance:
After processing, the system provides relevant legal advice, suggesting potential legal actions based on the description of the incident.
### Streamlit Interface: 
The system is deployed through a user-friendly Streamlit interface, enabling easy access and interaction.

## Key Features
### Tokenization & Semantic Analysis: 
Breaks down user input into tokens and analyzes the semantics to understand the context.
### Error Correction & POS Tagging: 
Corrects common errors and identifies parts of speech to enhance understanding.
### Contextual Word Embeddings: 
Generates word embeddings that capture the context, improving the accuracy of legal recommendations.
### Cosine Similarity Matching: 
Measures the similarity between user queries and pre-defined legal sections to provide the most relevant advice.
### L2 Normalization: 
Ensures uniformity in vector magnitude, improving the consistency of results.
### Top-10 Recommendation Accuracy: 
Utilizes a top-10 ranking system to provide the most relevant legal actions, improving decision-making for the user.

## Dataset
The system uses a custom dataset derived from legal documents and real-life incident reports. The dataset is tokenized and processed to create embeddings that are used for comparison with user queries.

## Model
The core of the system is a fine-tuned BERT model:

### Pre-training:
The model was pre-trained on large amounts of legal text to capture the nuances of legal language.
### Fine-tuning:
Fine-tuned using specific legal cases related to criminal violence to ensure relevance and accuracy.
### Embeddings: 
Word and sentence embeddings are generated to understand and match user inputs with relevant legal sections.

## Future Work
The system can be further improved by:

### Expanding the Dataset: 
Including more diverse legal cases to cover a broader range of criminal violence scenarios.
### Enhanced NLP Models: 
Experimenting with newer models and techniques for better performance.
### Multilingual Support: 
Extending the system to support multiple languages to cater to a broader audience.


