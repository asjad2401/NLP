# NLP  
This folder contains two different approaches to make an article sorter.   
## Dataset  
The data set used to train this model was taken from Kaggel. It contains 2000 articles sorted into 5 different categoties.  
## Word2Vec  
The first approach converts words in articles to vectors in a vector space and these vectors are passed to softmax regression NN.  
## Bert Embeddings  
The second approach uses Transforrmers to generate BERT embeddings from the text of articles. The best embeddings are context aware and put the similar words close together in the vector space.  
