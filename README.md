# Fine-tuning BERT for Custom Named Entity Recognition (Token Classification)   


Project Highlights
-----

**I delivered a BERT-based model that was fine-tuned with small volume of data to extract all technology terms from any given article (F1 scores > 90%)** 

I built a pipeline of:
- cleaning & preprocessing train and test data for BERT
- fine-tuning the BERT model with train set
- validating the fine-tuned BERT model performance (F1 score, confusion table) for both train and test set,
- saving the fune-fined BERT model and tokenizer,
- using the fune-fined BERT model and tokenizer for inference (identifying technology terms and extract them from any new articles)


Install dependencies
-----
$ pip install -r requirements.txt

Usage
-----

$ python3 main.py

Deployment
-----

I deployed the fine-tuned BERT model as a web app with Docker in Azure. The app can help users extract technology terms from articles in multiple ways. Please find the code for the web app deployment in this [repo](https://github.com/ensembles4612/technology_term_extractor_app_streamlit_deployed_on_azure).
