# Content-Analysis-Project
# Discovering Product Differences from Consumer Reviews

Group Member: Yimin Li, Li Liu, Yuming Zhu

## Introduction
We usually rely on or refers to customers’ reviews when shopping online. Although shopping platforms always recommend us some products by all means, we tend to keep minds clear and find the one we like and we believe in. However, even if we find the best seller with over thousands reviews and over four-star in score, and carefully read some long reviews that seem to include thorough information, we still bypass too much of the power of reviews. Hence, this project aims to provide a prototype of an information revealing system of customers’ reviews.

## Data
We wuse Amazon Review Data (2018, https://nijianmo.github.io/amazon/index.html) as our main dataset for content analysis. It is a huge dataset released by UCSD researchers with a total number of reviews of 233.1 million ranging from 1996 to 2018. For each product in the data, the data provides detailed information on its characteristics, such as color, price, package type, descriptions, technical details, similar products, image features, categories information, sales rank, to name a few. For each review associated with the product, it has the reviewer’s name, ratings, text, summary, attached image URL, and helpfulness votes, the label for verified purchase, and so on.

In terms of time and In this project, we specifically used five keyboard reviewed data selected from the huge Amazon Review Data as the pivot study for this study. We selected five keyboard products with abudant amount of reviews on Amazon coming from five different brands, with a total query of 5,500 queries.

## Methods
Figure 1 shows the design of our algorithm. Firstly, the users could provide several similar products that they are considering buying. Then the algorithm could identify the unique ASIN codes that Amazon uses for these products. Secondly, the algorithm would fetch and sample the associated consumer reviews by the ASIN codes and then pre-processed them. Thirdly, the algorithm would do three parts of analysis in parallel, which are exploratory data analysis, topic modeling, and word embedding. Lastly, the results will be
combined to generate a product comparison infographic that quantify the differences ofproduct within reviews.

![image](https://github.com/liu431/Content-Analysis-Project/blob/master/Code/Plots/Algo.png)

## Results
Combining the result from the methods (Counting Words, Sentiment Analysis, Topic Modeling, Doc2Vec, and Score Function), Figure 14 provides a infographic that could help consumers make easier decisions by quantifying the product differences from consumer reviews. For example, if the consumer is interested in picking up a keyboard that is both popular and with a trustworthy seller, the Azio keyboard would be the best option as it satisfies these criteria.

Also, this infographic is the prototype of an algorithmic product that we are building. To solve consumers’ decision problem, we plan to build a web app where users could type in the names of products that they are comparing. The web app could generate a infographic automatically that helps consumers accelerate decisions without spending too much time in reading reviews.

![image](https://github.com/liu431/Content-Analysis-Project/blob/master/Code/Plots/infographic.png)
