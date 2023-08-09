# Llama2-Medical-Chatbot
This is a medical bot built using Llama2 and Sentence Transformers. The bot is powered by Langchain and Chainlit. The bot runs on a decent CPU machine with a minimum of 16GB of RAM.

## Create Virtual Environment

```
python3 -m venv venv
```

## Upgrade Pip (Package Manager)

```
pip install --upgrade pip
```

## Install packages

```
pip install -r requirements.txt
```

## Store embeddings

```
python3 ingest.py
```

## Load embeddings & run chatbot

```
chainlit run model.py -w
```
