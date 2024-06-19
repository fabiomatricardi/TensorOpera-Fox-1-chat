# TensorOpera-Fox-1-chat
Chat with web-based Document search and TensorOpera Fox-1 LlamaCPP

<img src='https://blog.tensoropera.ai/content/images/size/w1200/2024/06/fox-logo--1--3.jpg' height=400>


## Description
project to talk with documents retrieved with websearch and enriched with newspaper3k
forced to use llama-cpp-python and not llamafile becuase of the embeddings
<br>
> Using langchain for both llamaCPP LlamaCppEmbeddings and ChatLlamaCpp


## MODEL USED: TensorOpera Fox-1
https://blog.tensoropera.ai/tensoropera-unveils-fox-foundation-model-a-pioneering-open-source-slm-leading-the-way-against-tech-giants/

We are thrilled to introduce TensorOpera Fox-1, our cutting-edge 1.6B parameter small language model (SLM) designed to advance scalability and ownership in the generative AI landscape. TensorOpera Fox-1 is a top-performing SLM in its class, outperforming SLMs developed by industry giants like Apple, Google, and Alibaba, making it an optimal choice for developers and enterprises looking for scalable and efficient AI deployment.

## Create Venv
python311 -m venv venv
➜ venv\Scripts\activate
(venv) ➜ llamacpp-agents ⚡                                                                                             3.11.7

### install dependencies
```
pip install --upgrade langchain langchain-community faiss-cpu tiktoken duckduckgo-search llama-cpp-python rich newspaper3k easygui lxml_html_clean streamlit
```

### Download GGUF files
from Hugging Face Repo https://huggingface.co/QuantFactory/Fox-1-1.6B-GGUF/tree/main


#### RESOURCES:
https://python.langchain.com/v0.2/docs/integrations/chat/llamacpp/

https://python.langchain.com/v0.1/docs/integrations/text_embedding/llamacpp/

https://python.langchain.com/v0.2/docs/concepts/#documents

https://python.langchain.com/v0.1/docs/integrations/tools/ddg/

https://stackoverflow.com/questions/77782167/modulenotfounderror-no-module-named-langchain-openai

https://python.langchain.com/v0.2/docs/integrations/chat/openai/

