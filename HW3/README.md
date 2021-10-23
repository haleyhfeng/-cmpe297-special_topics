# HW 3

**Objective**: Implement five different fine tuning task types using BERT.

**Build with**:
* _**BERT - Classification**_ (1) 
: classify text as grammatically correct/incorrect using GLUE fine-tuned with distilbert-base-uncased model
<img width="999" alt="Screen Shot 2021-10-23 at 3 27 30 AM" src="https://user-images.githubusercontent.com/46875754/138552615-951a5a5f-adc8-4eda-8757-f63ba095f042.png">

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
<img width="1368" alt="Screen Shot 2021-10-23 at 3 33 32 AM" src="https://user-images.githubusercontent.com/46875754/138552668-24f63f0d-530d-4b1b-8680-d37432c65ccf.png">


Reference/Modified code from the following notebooks: 
* https://huggingface.co/transformers/notebooks.html
* https://github.com/chuachinhon/gradio_nlp/tree/main/notebooks

