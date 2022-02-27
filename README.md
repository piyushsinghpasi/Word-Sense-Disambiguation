# Implementing WSD using HMM-Viterbi and Word Embedding Overlap

**Platform** : Python Jupyter, Google Colab or VS Code.  
VS Code (version 1.59.0) was used to run the code. 

## Common libraries used in the implementation of WSD
nltk (version 3.2.5)  
numpy (version 1.19.5)  
pandas (version 1.1.5)  
pickle (version 4.0)  
regex (version 2019.12.20)  
seaborn (version 0.11.1)  
sklearn (version 0.24.2)  
matplotlib (version 3.2.2)  
wordnet (version 3.0)
### Additional library used in bigram based implementation
ipywidgets (version 7.6.3)

## Dataset required
Run the following command in terminal to download GoogleNews dataset in the models folder we have made: <br/>
wget -c "https://s3.amazonaws.com/dl4j-distribution/GoogleNews-vectors-negative300.bin.gz"

## Running the code
### Running HMM_WSD_POS_Bigram.ipynb and HMM_WSD_POS_Trigram.ipynb

"word_synset_tuple" use this function to transform your data.

The section "Train function" contains the function to train the model given the training data.  

The "Test function" section contains the function which tests the model using the generated transmission and emission probabilities.  

**Run all the cells** to generate overall metrics of the model.

Both the files HMM_WSD_POS_Bigram.ipynb and HMM_WSD_POS_Trigram.ipynb use POS tags to generate the output with bigram and trigram assumption respectively.

## Running WSD_Part2.ipynb ( Word Embedding Overlap )
word2vec requires the following file: GoogleNews-vectors-negative300.bin.gz

**Run all the cells**.

## 
***Error Analysis has been added in the code and the slides***

###### Caution:
Run all cells for functions to be defined, Note and Cautions are mentioned in the Notebook as well  

## References

https://www.fi.muni.cz/tsd2002/papers/92_Antonio_Molina.pdf 

http://csci572.com/papers/SpeechLanguageProc.pdf  

https://nlp.stanford.edu/~wcmac/papers/20050421-smoothing-tutorial.pdf  

https://web.stanford.edu/~jurafsky/slp3/3.pdf  

https://aclanthology.org/E17-1010.pdf

http://nlpprogress.com/english/word_sense_disambiguation.html

