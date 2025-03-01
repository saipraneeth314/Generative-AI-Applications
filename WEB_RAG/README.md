# WEB RAG – Retrieval-Augmented Generation for Web-Based Knowledge Retrieval

## Overview
Built a Web-Based *Retrieval-Augmented Generation (RAG)* System that enhances knowledge retrieval by combining search-based retrieval with generative AI models. This project enables accurate, context-aware responses by leveraging large-scale text data, making it highly valuable for applications like medical research, legal document analysis, and enterprise knowledge management.

## Installation
To install the required dependencies, run:
```bash
pip install -r requirements.txt
```

## Usage
1. **Set Up the Environment**  
   Install the required dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  

2. **Specify the Target Website**  
   Update the script with the website URL from which data needs to be retrieved. Ensure the website allows web scraping by reviewing its `robots.txt`.  

3. **Run the Retrieval Script**  
   Execute the script to fetch and process data from the specified website:  
   ```bash
   python retrieve_data.py
   ```  

## Dependencies
The project requires the following Python libraries:
```
bs4
getpass
langchain
langchain_community
langchain_core
langchain_huggingface
langchain_text_splitters
langgraph
os
warnings
```
