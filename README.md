
# LangChain Documentation Helper

A repository for learning LangChain by building a generative ai application.

This is a web application is using a Pinecone as a vectorsotre and answers questions about LangChain 
(sources from LangChain official documentation). 


![Logo](https://github.com/anikesh-mane/Langchain-Documentation-Chatbot/blob/e11bfa6c12bceb0c1e1b4036c2e746b5bc7ad159/static/banner.gif)

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`PINECONE_API_KEY`
`PINECONE_ENVIRONMENT_REGION`
`OPENAI_API_KEY`

## Run Locally

Clone the project

```bash
  git clone https://github.com/emarco177/documentation-helper.git
```

Go to the project directory

```bash
  cd documentation-helper
```

Download LangChain Documentation
```bash
  mkdir langchain-docs
  wget -r -A.html -P langchain-docs https://python.langchain.com/en/latest/index.html
```

Install dependencies

```bash
  pipenv install
```

Start the flask server

```bash
  streamlit run main.py
```


## Running Tests

To run tests, run the following command

```bash
  pipenv run pytest .
```
