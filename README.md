# SMS_Summary
Project focuses on generating sms_summaries

# Libbraries
- import spacy
- import en_core_web_sm
- import pandas as pd
- import nltk
- import re
- from transformers import pipeline
- from transformers import AutoTokenizer, AutoModelForSeq2SeqLM
- from keybert import KeyBERT
- import json

# Hugging Face Documentation

- Model Used = facebook/bart-large-cnn
- Link - https://huggingface.co/facebook/bart-large-cnn

# Issues to tackle

- Integrating transformer models with mobile application.
- may be impossible
- Then look for the extractive summarization using summy library
