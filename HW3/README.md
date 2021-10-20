# HW 3

**Objective**: Implement five different fine tuning task types using BERT.

**Build with**:
* _**BERT - Classification**_ (1) 
: classify text using GLUE fine-tuned with distilbert-base-uncased model
* _**BERT - Summarization**_ (2) 
: summarize text using XSum dataset fine-tuned with t5-small  
* _**BERT - Question-Answering**_ (3) 
: question and answering using SQuAD dataset fine-tuned with distilbert-base-uncased model
* _**BERT - Translation**_ (4) 
: translate text using WMT dataset fine-tuned with Helsinki-NLP/opus-mt-en-ro 
* _**BERT - Entity Recognition**_ (5) 
: extract entity from text 

**Techniques applied**:
* **Text Preprocessing** 
* **Transfer Learning**
* **Deployment with Gradio Web App**
* **Log with Tensorboard**

Reference/Modified code from the following notebooks: 
* https://huggingface.co/transformers/notebooks.html
* https://github.com/chuachinhon/gradio_nlp/tree/main/notebooks

