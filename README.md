# Classifying-NLP-papers
Classifying papers on NLP on basis of abstract 
nlp.txt :: 
    This is manually labelled papers with format --> file_names, labels()
    Labels -->>
        Speech = papers on spoken language, or speech related.
        Translation = papers on translation, transliteration
        IE = Information Extraction
        Summarization = Summarization of texts.
        QA = question answers.
        Lexical = papers based on lexical
        Grammar = papers based on grammars
        NE = Named Entity

vocab.txt ::
    This files contains vocabulary that are extracted from files and is used to make processed.txt.

processed.txt ::
    This file contains filtered words that are extracted from original raw data.
 
NLP_data_preparation.ipynb ::
    This file takes input npl.txt which contains file names and then it applies prerpocessing techniques to obtain vocab.txt and processed.txt.
    
NLP_model.ipynb ::
    This file contains model which take input npl.txt and processed.txt. This is not the best model there is lot of sope for improvement.

You can mail me at sourabhharlie143@gmail.com for dataset used and any clarifications , i will be glad to help you out.
