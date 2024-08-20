# Online Fraud Detection
 using LLM's to store database and query 



# Online Fraud Helpline: Question and Answer System Based on Google Palm LLM and Langchain for Online Fraud Detection and Prevention 

This is an end to end LLM project powered by Google's PaLM (Pathways Language Model) and Langchain. We are building a Chatbot system trained on a custom FAQ dataset focused on Online Fraud Detection and Prevention. Codebasics sells data related courses and bootcamps. They have thousands of learners who uses discord server or email to ask questions. This system will provide a streamlit based user interface for users where they can ask questions and get answers which helps them to identify, understand, and prevent various types of online fraud by providing accurate and quick responses to common queries.

## Why Online Fraud Detection Matters
Online fraud continues to rise as more people conduct transactions and share information digitally. Common types of online fraud include phishing, identity theft, online scams, and unauthorized transactions. Educating individuals about these threats is crucial in helping them avoid falling victim to such activities.



## Project Highlights

- Uses a customized dataset that contains FAQs regarding Online Fraud Detection and Prevention
- We will build an LLM(Google Palm) based chatbot system that can answer user questions based on the responses within the CSV file 
- Users should be able to use this system to ask questions directly and get answers within seconds

## You will learn following,
  - Langchain + Google Palm: LLM based Q&A
  - Streamlit: UI
  - Huggingface instructor embeddings: Text embeddings
  - FAISS: Vector databse

## Installation

1.Clone this repository to your local machine using:

```bash
  git clone https://github.com/SaiPuneeth2504/Online-Fraud-Detection
```

2. Install the required dependencies using pip:

```bash
  pip install -r requirements.txt
```
3.Acquire an api key through makersuite.google.com and put it in .env file

```bash
  GOOGLE_API_KEY="your_api_key_here"
```
## Usage

1. Run the Streamlit app by executing:
```bash
streamlit run main.py

```

2.The web app will open in your browser.

- To create a knowledebase of FAQs, click on Create Knolwedge Base button. It will take some time before knowledgebase is created so please wait.

- Once knowledge base is created you will see a directory called faiss_index in your current folder

- Now you are ready to ask questions. Type your question in Question box and hit Enter

## Sample Questions
  - What is deepfake fraud and how can I protect against it?
  - What is catfishing and how can I avoid falling victim to it?
  - How can I protect my personal information on social media?
  - IWhat is pharming and how does it differ from phishing?
  - What is a data breach and what should I do if I'm affected?

## Project Structure

- main.py: The main Streamlit application script.
- FraudDetection.py: This has all the langchain code
- requirements.txt: A list of required Python packages for the project.
- .env: Configuration file for storing your Google API key.
