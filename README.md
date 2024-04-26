# BERT-to-BERT-Text-Attack
## Objective: Are text classification models really robust!! 
* DataSet taken as Ag-news 
* Implemented application of non-targeted attack
* Implemented famous pre-trained transformer model (i.e., BERT-Base)
* Both dataset and language models are sourced from the **Hugging Face** Community
* Example given below: 
* **Original Text :** Oil and Economy Cloud Stocks' **[[Outlook]]** (Reuters) Reuters - Soaring crude prices plus worries\about the economy and the outlook for earnings are expected to\hang over the stock market next week during the depth of the\ **[[summer]]** doldrums.
* **Perturbed Text:** Oil and Economy Cloud Stocks' **[[climate]]** (Reuters) Reuters - Soaring crude prices plus worries\about the economy and the outlook for earnings are expected to\hang over the stock market next week during the depth of the\ **[[monsoon]]** doldrums.
* Due to this perturbation; target label changed from **[[Business (100%)]] --> [[Sci/tech (88%)]]**
