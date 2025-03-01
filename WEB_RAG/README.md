# WEB RAG – Retrieval-Augmented Generation for Web-Based Knowledge Retrieval

## Overview
This project is a **Retrieval-Augmented Generation (RAG)** application that retrieves data from a specified website and enhances text-based retrieval with generative AI capabilities.

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
