# Llama2-Medical-Chatbot
This is a medical bot built using Llama2 and Sentence Transformers. The bot is powered by Langchain and Chainlit. The bot runs on a decent CPU machine with a minimum of 16GB of RAM.

## Create Virtual Environment

```
conda -V
```

```

```

## Upgrade Pip (Package Manager)

```
python -m pip install --upgrade pip
```

## Install packages

```
python -m  pip install -r requirements.txt
```

## Store/Update embeddings

```
python -m ingest
```

## Load embeddings & run chatbot

```
chainlit run model.py -w
```

How a Doctor would diagnose Eczema?



lsof -i TCP:8000 | grep LISTEN

pip install urllib3==1.26.6


https://stackoverflow.com/questions/76187256/importerror-urllib3-v2-0-only-supports-openssl-1-1-1-currently-the-ssl-modu

 NotOpenSSLWarning: urllib3 v2.0 only supports OpenSSL 1.1.1+, currently the 'ssl' module is compiled with 'LibreSSL 2.8.3'. See: https://github.com/urllib3/urllib3/issues/3020

  warn("The installed version of bitsandbytes was compiled without GPU support. "
'NoneType' object has no attribute 'cadam32bit_grad_fp32'

 been used. Disabling parallelism to avoid deadlocks...
To disable this warning, you can either:
        - Avoid using `tokenizers` before the fork if possible
        - Explicitly set the environment variable TOKENIZERS_PARALLELISM=(true | false)