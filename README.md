# CUNY_NLP_Network_Analysis_Project_Samples

## Data 620 Final Project
### Pride and Prejudice and Oliver Twist - A Comparison Using Network Analysis and Text Processing
Jit Seneviratne and Sheryl Piechocki  
July 17, 2020

**Data**  
The data used in this project is the texts of two classic books, <u>Pride and Prejudice</u> by Jane Austen and <u>Oliver Twist</u> by Charles Dickens.  The text of both of these books is available on the Project Gutenberg website. 

Sources: 
* [Pride and Prejudice](https://www.gutenberg.org/files/1342/1342-0.txt)
* [Oliver Twist](http://www.gutenberg.org/cache/epub/730/pg730.txt)

**Analysis**  
After reading in the text of both books, they were cleaned and lemmatized and split into chapters.  Network analysis of the character projections was performed, including degree centrality and betweenness centrality measures.  Network graphs by volume were created to determine how the character networks changed over time in the books.  

Text analysis for each book includes the count of unique words, Zipf's law examination, most frequent words by chapter, character vector similarity using Word2Vec, and sentiment analysis at a sentence level for each chapter and compare the two novels for their general sentiment.

* [Video clip Part 1](https://youtu.be/KuO9669ACfg)
* [Video clip Part 2](https://youtu.be/VXr41OFjU6A)

## Data 620 Project 1
### Centrality Measures Across Categorical Groups

Jit Seneviratne and Sheryl Piechocki
June 17, 2020

The video clip was longer than 15 mins, so we split it into two clips:

[Video Link - 1](https://youtu.be/3hBrb_QDUEM)

[Video Link - 2](https://youtu.be/GGCfWHTUBAA)

**Dataset** 
The data used in this project is from SG&R law firm, a U.S. corporate law firm in New England. It contains network measurements for 71 attorneys from 1988-1991. There are three types of relationships measured, i.e. co-worker, advice, and social. Attorneys are classified as partners or associates and the data contains gender classification.

**Co-worker Network** 
Attorneys were asked to go through a list of names and mark off those that they had worked with in the last year, either working on the same case or reading/using some of each other's work product.

**Advice Network** 
Attorneys were asked to go through a list of names and mark off those that they had gone to for professional advice in the last year.

**Social Network**
Attorneys were asked to go through a list of names and mark off those that they had socialized with outside of work.

Source: http://moreno.ss.uci.edu/data.html#lazega

## Data 620 Project 2
### 2-Node Network Analysis
Jit Seneviratne and Sheryl Piechocki 
June 27, 2020

[Video clip](https://youtu.be/YLlleV99NLQ)

**Dataset**
The data used in this project is from a database compiled by Olival, K., Hosseini, P., Zambrana-Torrelio, C. et al in 2017. It contains  2,805 mammal–virus associations, including 754 mammal species 586 unique viral species.  Also included is a measure of detection for the association that relates to the quality of the association.  Included attributes are virus genus and mammal classification of wild vs. domestic.  

Source: Olival, K., Hosseini, P., Zambrana-Torrelio, C. et al. Host and viral traits predict zoonotic spillover from mammals. *Nature* 546, 646–650 (2017). https://doi.org/10.1038/nature22975  
Data: https://zenodo.org/record/807517#.XveDWPXPxPY

**Analysis:**
The association, virus, and hosts files will be loaded for analysis.  Common names will be mapped to hosts.  The bipartite network will be projected onto both a hosts and virus sub-network.  Hosts and virus networks will be analyzed using various centrality measures and reduced to visualize clusters. We will also be looking at which hosts could potentially carry viruses to other hosts.

***Emphasis on Coronavirus:***
Given the current situation involving COVID-19 we paid special attention to the network surrounding viruses of the genus 'Coronavirus', 'Alphacoronavirus' and 'Betacoronavirus'.


