# Content-Analysis-Project

## Group Member: Li Liu, Yuming Zhu, Yimin Li

## Introduction
New innovations in natural language processing (such as BERT) have enabled researchers to summarize the Amazon reviews text efficiently. However, reviews are not created equal as they may have different impacts on consumers' purchase decision. Thus, we hypothesize that the summaries would be more helpful if the algorithm trains the reviews with different weights. Using ensemble feature selection methods, we find the features that are most helpful for consumers and calculate the weights for the reviews. Then we train the text generation/summarization algorithm to create new summaries that match consumers' needs. To measure the improvement, we run experiments and let the coders to score the summarizes in terms of helpfulness.  

## Data
We would use Amazon Review Data (2018, https://nijianmo.github.io/amazon/index.html) as our main dataset for content analysis. It is a huge dataset released by UCSD researchers with a total number of reviews of 233.1 million ranging from 1996 to 2018. Among the huge dataset, we chose three sub-categories (Electronics, Pet Supplies, Video Games) for further content analysis with a total review number of 9.35 million reviews. This dataset provides us with abundant information for content analysis, including reviews’ summary, reviews’ text, overall score, product ID, product price etc., functioning as the natural experiment for our content analysis.

## Methods
This project combines a list of methods including content analysis, machine learning, deep learning etc. and it would cover abundant techniques learnt from Computational Content Analysis. After cleaning the data from Amazon Review Data, we would apply feature selection models to test which feature of the review text might play a more important role on consumers’ purchase decision. After that, we would use deep learning models to train text generation algorithm and generate the new, high-level summaries that match consumers’ needs. Finally, if time permitted, we would recruit coders to manually test whether our new summaries would be helpful or not. 

## Reference
Ni, J., Li, J., & McAuley, J. (2019, November). Justifying Recommendations using Distantly-Labeled Reviews and Fine-Grained Aspects. In Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP) (pp. 188-197).

