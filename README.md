# LangChain - Chatbot for your PDF Documents

This Python code based on the LangChain framework is designed to answer questions from a PDF document; your PDF document. It utilizes natural language processing techniques to extract information from the document and generate accurate answers.

## Description

This project aims to automate the process of answering questions based on the content of a PDF document. It utilizes the LangChain framework, which combines the power of deep learning models and language processing algorithms to understand the context of the questions and extract relevant information from the PDF.

The framework uses a pre-trained language model (Google Flan T5 and GPT2 from hugging face or Cohere) to comprehend the document's content and provides question-answering algorithms to generate accurate responses. It supports a wide range of question types, including factual, descriptive, and inferential questions.

## Features

- Extracts text content from PDF documents.
- Processes and cleans the extracted text for better understanding.
- Uses a pre-trained language model to comprehend the document content.
- Implements question-answering algorithms to generate answers.
- Supports various question types and provides accurate responses.

## Requirements

To run this code, you need the following dependencies:

- Python 3.9.6 or higher
- LangChain framework
- PyPDF4 
- pdfplumber

## Installation

The basic `pip` or `pip3 install <package name>` does the job for most of the dependencies. 

## Usage

To use the LangChain Question Answering framework, follow these steps:

1. Place your PDF document in the `pdfs` folder.
2. Rename `copy.env` file to `.env` and add your API keys for Huggingface and Cohere. 
3. Update the PDF path variable `file_path`. The Jupyter notebook is commented on for your convenience as well.
4. Follow the instructions for the notebook [PDF-Chatbot.ipynb](https://github.com/affanbinusman/LangChain_PDF-Chatbot/blob/main/PDF-Chatbot.ipynb). A prompt will pop up for you to type in your question. 

## Examples

Here are some examples:
Question: Can Artificial Intelligence Concentration students opt for portfolio option?
Answer: Yes, they can.

Question: The Graduate Student Handbook for Robotics program is intended for which academic year?
Answer: The relevant sentence in the text is: The Graduate Student Handbook for Robotics program is intended for 23-24 AY.
So, the answer is 23 - 24 AY.
