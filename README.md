# Content-Analysis-Project
Zhu_Li_Li

Group Member: Li Liu, Yuming Zhu, Yimin Li

## Introduction
We usually rely on or refers to customers’ reviews when shopping online. Although shopping platforms always recommend us some products by all means, we tend to keep minds clear and find the one we like and we believe in. However, even if we find the best seller with over thousands reviews and over four-star in score, and carefully read some long reviews that seem to include thorough information, we still bypass too much of the power of reviews. Hence, this project aims to provide a prototype of an information revealing system of customers’ reviews.

## Data
We would use Amazon Review Data (2018, https://nijianmo.github.io/amazon/index.html) as our main dataset for content analysis. It is a huge dataset released by UCSD researchers with a total number of reviews of 233.1 million ranging from 1996 to 2018. Among the huge dataset, we chose three sub-categories (Electronics, Pet Supplies, Video Games) for further content analysis with a total review number of 9.35 million reviews. This dataset provides us with abundant information for content analysis, including reviews’ summary, reviews’ text, overall score, product ID, product price etc., functioning as the natural experiment for our content analysis.

In terms of time and In this project, we specifically used five keyboard reviewed data selected from the huge Amazon Review Data as the pivot study for this study. We selected five keyboard products with abudant amount of reviews on Amazon coming from five different brands, with a total query of 5,500 queries.

## Methods
Figure 1 shows the design of our algorithm. Firstly, the users could provide several similar products that they are considering buying. Then the algorithm could identify the unique ASIN codes that Amazon uses for these products. Secondly, the algorithm would fetch and sample the associated consumer reviews by the ASIN codes and then pre-processed them. Thirdly, the algorithm would do three parts of analysis in parallel, which are exploratory data analysis, topic modeling, and word embedding. Lastly, the results will be
combined to generate a product comparison infographic that quantify the differences ofproduct within reviews.



## Reference
Ni, J., Li, J., & McAuley, J. (2019, November). Justifying Recommendations using Distantly-Labeled Reviews and Fine-Grained Aspects. In Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP) (pp. 188-197).

