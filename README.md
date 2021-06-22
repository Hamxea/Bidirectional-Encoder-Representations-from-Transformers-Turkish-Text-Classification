# Bidirectional-Encoder-Representations-from-Transformers-Turkish-Text-Classification
Bidirectional Encoder Representations from Transformers: Turkish Text Classification.

The use of Bert pre-trained model takes less time to train the model we fined-tuned in this study, with 2-4 epochs maximum to get good result. this  may be due to the fact, Bert model consisted of embedding information about most of the languages. We just need to tweak the output layer and use it to out features  to conform with our classification task. 
As shown in the table below, the result shows that a simple fine-tuning and adding a layer on top of a Bert model and train it with less epochs results to achieving good result in our experiment. This indicate that simply fine-tuning BERT is shown to be a better (or at least equal) alternative to state of the art results the literature. Moreover, the result shows that with small dataset we can achieve a reasonable accuracy compared to the other NLP models that require large amount of dataset to train their model.


![Screenshot_1](https://user-images.githubusercontent.com/27901245/105993874-ed36b800-60b7-11eb-81c1-5a69e6481402.png)



![Screenshot_3](https://user-images.githubusercontent.com/27901245/105987195-00915580-60af-11eb-9a20-aa8d0c822e5f.png)

