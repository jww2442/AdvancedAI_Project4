# AdvancedAI_Project4
NOTE: To use this project, all four data files (new_gift_cards.json, masked_nouns.csv, masked_verbs.csv, masked_adj.csv) must be uploaded to the /home directory of the notebook. This project was done in Google Colab. Link here: https://colab.research.google.com/drive/1759dy7U5OX7nQEs41S3quytB9HeM0QCm?usp=sharing 

Working with Transformer models. Applications used: GPT-2 text generation, Amazon review sentiment analysis, and Masked Language Modeling

This was a lone project. We used HuggingFace Co.'s Transformer models to perform the above stated tasks. I have attached my report. 

The project specifications are pasted below: 
----------------------------------------------------------------------------------------------

You will use a pre-trained tranformer model (provided by Hugging Face Co; usage details) in this project (follow the Google Colab project link; IMPORTANT - Make a copy of this colab notebook before working on it).  You will apply these models to do the following tasks:

Task 1:  Text generation from multiple 1, 5, and 10 word prompts
Task 2: Sentiment analysis of user reviews of products from a selected category sold on Amazon 
Task 3: Predicting missing words (masked language modeling). 
Submit a report of at least a page (1" margin, 12 pt font, A4 paper) per task containing the following:

Representative output summarizing your work, your analysis and takeaways. (90% of project grade)
Also Suggest possible applications of these tasks or other tasks that you have tried with the models.  (10% of project grade)
Update: The datasets for Task 3 are now available and attached to this harvey post. There are 3 files: masked_nouns.csv, masked_verbs.csv, and masked_adjs.csv, each with 500 data pairs. 

Each file follows the format:

"masked text", "target word"

The masked word is replaced with "__MASKED__" in the masked text. You will have to replace these with the transformers package's "{tokenizer.mask_token}" as shown in https://huggingface.co/transformers/task_summary.html#masked-language-modeling 
