# Freedom-of-Information-Act-Thesis-2024
Enhancing the Machine Readability of Government Documents Published under the Woo: An Evaluation of ChatGPT's Effectiveness and Impact on NLP Tasks
Code for thesis project Information Studies: Data Science, University of Amsterdam (2023-2024)
Student: Oumayma Salma El Kadi

# Data sets
1. besluitenlijsten.csv provided by Maarten Marx from Woogle 
2. dutch_wordlist.txt retrieved from https://github.com/OpenTaal/opentaal-wordlist 
3. DataAfterRepair.csv is the besluitenlijsten.csv right after the reparation by ChatGPT is done
4. DataFrameRepairFinished.csv is the updated version of the DataAfterRepair.csv where the sentiment analysis is done (provided to save runningtime for the sentiment analysis)
5. sample_30_human_evaluation.csv this sample consists of random 30 decision letters. Each letter has been rewritten by the human evaluator to serve as the ground truth to perfom the human evaluation on.

# Abstract
This thesis aims to improve the machine readability of governmental documents in the Netherlands by using natural language processing techniques. Many of these documents currently lack machine readability, which hinders their accessibility and analytical potential. Optical character recognition (OCR) is used to extract text from scanned documents, but the accuracy of the extracted data is limited due to incorrect conversions. To address this issue, the study utilizes diverse NLP techniques to analyze the OCR-generated documents. The AI chatbot, ChatGPT 4.0, is employed to enhance the OCRed text by repairing sentences with misspelled words. The quality of the OCR documents is assessed using word error rate, and various NLP similarity metrics are applied to compare the OCRed text with the repaired text. The use of artificial intelligence for text restoration is a valuable contribution to scientific knowledge. The results demonstrate that ChatGPT 4.0 significantly improves the accuracy of OCR error correction. Metrics such as Levenshtein Distance, Jaccard Similarity, TF-IDF Cosine Similarity, and semantic similarity consistently show improved alignment between the cleaned and repaired texts, indicating the model's ability to handle Dutch language nuances and context-specific scenarios.

# Note
In order to be able to run the code, the secret API key should be provided. Running the latest version of the code costs approximately €50 (due to the huge amount of tokens processed by ChatGPT). Therefore the processed data was saved into new datasets that are provided to be able to run the code without costs. 

Do not run all cells, read the headers to avoid unnecessary runningtime!


   
