# In Case of Russian - BERT the Noun
A UC Berkeley MIDS W266 NLP Final Project Repository

**Abstract**

This paper explores the possibility of applying multilingual BERT Transformers to Grammar Error Correction of Russian cases. BERT-based morphological taggers have had excellent success identifying cases in correct sentences in Russian. However, I find that they struggle to deal with erroneous examples as information about the appropriate case is encoded not just in the noun form, but more importantly in the context, including verbs and prepositions. That led me to a BERT-based error-classification approach on a synthetic dataset of erroneous examples. The results demonstrate that case-pertinent information is encoded in pre-trained BERT models and can be harnessed for the task of building a case-error correction system.

**Contents:**

1. Final Submission Paper: W266__David_Djambazov.pdf

2. /workfiles
    
        /Multi-class RuCases_multiclass_MBERT_Fine_tuning_main.ipynb - Multi-class fine-tuned model
    
        /RuCases_MBERT_Fine_tuning_binary_main.ipynb - Binary fine-tuned model
    
        /ReCases_perturbed_dataset_gen_main.ipynb - dataset processing
    
        /load_saved_keras_model_main.ipynb - Result analysis and attention mapping
    
        /CNN_word2vec_RU_main.ipynb - Baseline CNN model with word2vec embeddings
    
        /RuCases_Word2Vec_main.ipynb - Word2vec embedding generation
    
NB: Please note that the notebooks in the repository are in a rather raw state and will be cleaned up in due time. Datasets, intermediate results, saved models, etc. are not part of this repository.
