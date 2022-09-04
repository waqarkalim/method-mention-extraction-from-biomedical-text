## Step 1 and Step 2 for the rule-based stage.
## Step 3 and Step 4 for the machine-learning stage.

## Step 1:
Run the 'convertData2StanzaedData.ipynb' notebook. It will read the one line, two line, and three line files (which are stored in the /dataset directory), after reading, it will run Stanza's dependency parser functions on it and retrieve relevant information (like the dependency relationship), and will store that information in a pickle file ('sentences_tok.pkl') 

## Step 2:
Run the 'complex_rule_based.ipynb' notebook. It will run the complex rules that we defined on the data from 'sentences_tok.pkl'. And it will store that data in another pickle file (called 'complex_rule_iob_input.pkl') and will also write the data in a text file (called 'complex_rule_iob_input.txt') in the format of a list of list of words where each word is in the format of (word, POS_tag, IOB_tag), e.g. ('Frozen', 'JJ', 'O').

## Step 2.5: (You don't need to re-run this step unless you change the dataset)
Run the 'word_embeddings_simplification.ipynb' notebook. It checks the data in 'complex_rule_iob_input.pkl' and finds the vectors for the words that are in our data from the word embeddings files (BioWordVec) and stores that data in a dictionary. This is done to just save up space in the Step 4 notebook, because there are around 16500000 vectors words in the whole word embeddings files, and after doing this, we end up with 5664 vectors. After that, the dictionary is stored in 'word_embeddings_dict.pkl' and used in Step 4.

## Step 3:
Run the 'method_mentions_crf_complex.ipynb' notebook. This will train, test, and report the performance metrics of the CRF model.

## Step 4:
Run the 'method_mentions_bi-lstm-crf_complex-rules.ipynb' notebook. This will train, test, and report the performance metrics of the Bi-LSTM model.


