# HW 3

**Objective**: Implement five different fine tuning task types using BERT.

**Build with**:
* _**BERT - Classification**_ (1) 
: classify text as grammatically correct/incorrect using GLUE fine-tuned with distilbert-base-uncased model
* _**BERT - Summarization**_ (2) 
: summarize a long piece of text using XSum dataset fine-tuned with t5-small  
* _**BERT - Question-Answering**_ (3) 
: simple question and answering using SQuAD dataset fine-tuned with distilbert-base-uncased model
* _**BERT - Translation**_ (4) 
: translate english text into Romanian using WMT dataset fine-tuned with Helsinki-NLP/opus-mt-en-ro 
* _**BERT - Causal Language Modeling**_ (5) 
: generate text to a sentence using Wikitext 2 dataset fine-tuned with distilgpt2 model

**Techniques applied**:
* **Text Preprocessing** 
* **Transfer Learning**
* **Deployment with Gradio Web App**
* **Log with Tensorboard**

Reference/Modified code from the following notebooks: 
* https://huggingface.co/transformers/notebooks.html
* https://github.com/chuachinhon/gradio_nlp/tree/main/notebooks

