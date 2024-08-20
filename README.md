# Online Fraud Detection
 using LLM's to store database and query 



# Online Fraud Helpline: Question and Answer System Based on Google Palm LLM and Langchain for Online Fraud Detection and Prevention 

This is an end to end LLM project powered by Google's PaLM (Pathways Language Model) and Langchain. We are building a Chatbot system trained on a custom FAQ dataset focused on Online Fraud Detection and Prevention. Codebasics sells data related courses and bootcamps. They have thousands of learners who uses discord server or email to ask questions. This system will provide a streamlit based user interface for users where they can ask questions and get answers which helps them to identify, understand, and prevent various types of online fraud by providing accurate and quick responses to common queries.




![](codebasics_q_and_a.png)

## Project Highlights

- Use a real CSV file of FAQs that Codebasics company is using right now. 
- Their human staff will use this file to assist their course learners.
- We will build an LLM based question and answer system that can reduce the workload of their human staff.
- Students should be able to use this system to ask questions directly and get answers within seconds

## You will learn following,
  - Langchain + Google Palm: LLM based Q&A
  - Streamlit: UI
  - Huggingface instructor embeddings: Text embeddings
  - FAISS: Vector databse

## Installation

1.Clone this repository to your local machine using:

```bash
  git clone https://github.com/codebasics/langchain.git
```
2.Navigate to the project directory:

```bash
  cd 3_project_codebasics_q_and_a
```
3. Install the required dependencies using pip:

```bash
  pip install -r requirements.txt
```
4.Acquire an api key through makersuite.google.com and put it in .env file

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
  - Do you guys provide internship and also do you offer EMI payments?
  - Do you have javascript course?
  - Should I learn power bi or tableau?
  - I've a MAC computer. Can I use powerbi on it?
  - I don't see power pivot. how can I enable it?

## Project Structure

- main.py: The main Streamlit application script.
- langchain_helper.py: This has all the langchain code
- requirements.txt: A list of required Python packages for the project.
- .env: Configuration file for storing your Google API key.
