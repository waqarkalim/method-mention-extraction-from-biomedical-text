
# Method Mention Extraction from Biomedical Text

## Abstract
> In the field of Natural Language Processing (NLP), extracting method mentions from biomedical text has been a challenging task. Scientific research papers commonly consist of complex keywords and domain-specific terminologies, and new terminologies are continuously appearing. In this research, we extract method terminologies from scientific text using both rule-based and machine learning techniques. We use linguistic features to extract method sentences and use the Stanza dependency parsing module for the rule-based methods to construct a Silver Standard biomedical corporus to be used with various machine learning algorithms. This thesis will provide a set of methodologies to automatically extract method mentions from scientific corpora. Our results show that it is possible to develop machine learning models that can automatically extract method mentions to a reasonable accuracy without the need for a gold standard dataset. 

## Results

#### Rule Based Model Results
| System  | Precision  | Recall  | F-Score  |
|---|---|---|---|
| Rule-based  | 97.59  | N/A  | N/A  |


#### Machine Learning Model Results
| System  | Precision  | Recall  | F-Score  |
|---|---|---|---|
| Conditional Random Field  | 83.58  | 85.49  | 84.53  |
| Bidirectional LSTM  | 68.42  | 39.39  | 50.00  |




## Screenshots

![Page 1](https://github.com/waqarkalim/method-mention-extraction-from-biomedical-text/blob/master/screenshots/Final_Progress_Report_Kalim_1.jpg)
![Page 2](https://github.com/waqarkalim/method-mention-extraction-from-biomedical-text/blob/master/screenshots/Final_Progress_Report_Kalim_2.jpg)
![Page 3](https://github.com/waqarkalim/method-mention-extraction-from-biomedical-text/blob/master/screenshots/Final_Progress_Report_Kalim_3.jpg)
![Page 4](https://github.com/waqarkalim/method-mention-extraction-from-biomedical-text/blob/master/screenshots/Final_Progress_Report_Kalim_4.jpg)
![Page 5](https://github.com/waqarkalim/method-mention-extraction-from-biomedical-text/blob/master/screenshots/Final_Progress_Report_Kalim_5.jpg)
![Page 6](https://github.com/waqarkalim/method-mention-extraction-from-biomedical-text/blob/master/screenshots/Final_Progress_Report_Kalim_6.jpg)
![Page 7](https://github.com/waqarkalim/method-mention-extraction-from-biomedical-text/blob/master/screenshots/Final_Progress_Report_Kalim_7.jpg)
![Page 8](https://github.com/waqarkalim/method-mention-extraction-from-biomedical-text/blob/master/screenshots/Final_Progress_Report_Kalim_8.jpg)
![Page 9](https://github.com/waqarkalim/method-mention-extraction-from-biomedical-text/blob/master/screenshots/Final_Progress_Report_Kalim_9.jpg)
![Page 10](https://github.com/waqarkalim/method-mention-extraction-from-biomedical-text/blob/master/screenshots/Final_Progress_Report_Kalim_10.jpg)
![Page 11](https://github.com/waqarkalim/method-mention-extraction-from-biomedical-text/blob/master/screenshots/Final_Progress_Report_Kalim_11.jpg)
![Page 12](https://github.com/waqarkalim/method-mention-extraction-from-biomedical-text/blob/master/screenshots/Final_Progress_Report_Kalim_12.jpg)

## Tech Stack

Python, Pandas, NumPy, Sklearn, Stanford's CoreNLP Toolkit (Stanza), Conditional Random Fields (CRFs), Bidirectional LSTMs (Bi-LSTMs)
  
  
## Feedback

If you have any feedback, please reach out to me at waqaar.199@gmail.com
