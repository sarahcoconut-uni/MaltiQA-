**MaltiQA:**  
This project focuses on developing a Multiple Choice Question Answering (MCQ QA) system for the Maltese language using transformer-based models

**Project Pipeline:**  
1.Audio Collection (Maltese TV / News Broadcasts)  
2.Speech-to-Text Transcription  
3.Raw Maltese Text Generation  
4.Automatic Question Generation using LLM  
5.Manual Dataset Cleaning and Review  
6.Dataset Construction  
7.BERT Fine-Tuning  
8.Performance Evaluation  

**Model Used:**  
- bert-base-multilingual-cased  
- BertForMultipleChoice

**Dataset Structure:**  
question, option_0, option_1, option_2, option_3, ans
