# Word2vec_With_Gensim

# What's Word2Vec
it's a 2 layer neural network to generate word embeddings given a text corpus  .
and here we talk about the famous exemple : 

King - Man + Women = Queen 

we can conclude that 2 words have the same Corpus , have similar embedding .
# Why we use Word2vec :
 * the machine dont understand text , so we should convert the text into numbers , thats why we should convert text into numeric input .

 * The second goal is to convert high dimensional feature to low dimentional feature.
 * Preserves relationship between words 
 * better results in lots of deep learning applications 



# Model Architecture  for Word2Vec :

* CBOW (Continuous bag of words) : Predict The target word from the context 

* Skip Gram : Predict the context from the Traget Word

# Choice Of Model :
 * CBOW : Small Corpus / Fast
 * Skip Gram : Large corpus / Slow



