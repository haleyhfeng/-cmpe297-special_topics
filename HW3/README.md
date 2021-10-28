# HW 3

**Objective**: Implement five different fine tuning task types using BERT.

**Build with**:
* _**BERT - Classification**_ (1) 
: classify text as grammatically correct/incorrect using GLUE fine-tuned with distilbert-base-uncased model
<img width="999" alt="Screen Shot 2021-10-23 at 3 27 30 AM" src="https://user-images.githubusercontent.com/46875754/138552615-951a5a5f-adc8-4eda-8757-f63ba095f042.png">

* _**BERT - Summarization**_ (2) 
: summarize a long piece of text using XSum dataset fine-tuned with t5-small  
<img width="990" alt="Screen Shot 2021-10-27 at 4 28 54 PM" src="https://user-images.githubusercontent.com/46875754/139161875-b3cce07b-b1de-4e66-9b87-b13e5edca532.png">

* _**BERT - Question-Answering**_ (3) 
: simple extractive question and answering using SQuAD dataset fine-tuned with distilbert-base-uncased model
<img width="1005" alt="Screen Shot 2021-10-27 at 5 03 10 PM" src="https://user-images.githubusercontent.com/46875754/139164251-32e6ec89-4dd6-4ff1-9199-4324171d9255.png">

* _**BERT - Translation**_ (4) 
: translate english text into Romanian using WMT dataset fine-tuned with Helsinki-NLP/opus-mt-en-ro
<img width="1002" alt="Screen Shot 2021-10-27 at 7 10 59 PM" src="https://user-images.githubusercontent.com/46875754/139174100-1bbff79e-eef1-4789-94ef-5e8aaff7f7c0.png">

* _**BERT - Causal Language Modeling**_ (5) 
: generate text to a sentence using Wikitext 2 dataset fine-tuned with distilgpt2 model
<img width="1007" alt="Screen Shot 2021-10-23 at 4 09 16 AM" src="https://user-images.githubusercontent.com/46875754/138553640-70316a63-f464-4393-83d3-acae7649035c.png">


**Techniques applied**:
* **Text Preprocessing** 
* **Transfer Learning**
* **Deployment with Gradio Web App**
* **Log with Tensorboard**
<img width="1368" alt="Screen Shot 2021-10-23 at 3 33 32 AM" src="https://user-images.githubusercontent.com/46875754/138552668-24f63f0d-530d-4b1b-8680-d37432c65ccf.png">


Reference/Modified code from the following notebooks: 
* https://huggingface.co/transformers/notebooks.html
* https://github.com/chuachinhon/gradio_nlp/tree/main/notebooks

