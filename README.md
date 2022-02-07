# Image-captioning
Image Captioning is one of those projcts that blends the Natural langauge Procssing and computer vision. It involves training of the neural networks on images and correspoding targets text sentences ( can be more than one). Further more this Models is trained on the flicker 8k dataset which Comprise of 80000 images and contains 5 captions for each image.

### Dataset : 

Dataset which is used comprises of different scences and all natural images. The captions in this dataset are around 40,000 which is 5 captions for each image. And all are natual spoken langauge regarding any scence or image. It was collected in 2015 to investigate multimodal learning schemes for unsupervised speech pattern discovery.

### Dataset from Kaggle datasets:-  https://www.kaggle.com/adityajn105/flickr8k/activity

### Model-Workflow:- 

#### 1. First Works with Natural language Processing on Captions:-
   *      1.    Text Preprocessing
             * a.    Text cleaning
             * b.    Removing Punctuation ('!"#$%&'()*+)
             * c.    Removing stopwords
             * d.    Lemmatize the words
             * e.    Tokenize the words of each captions
             * f.    pad the seqences and create the numpy array
   *     2. Tokenizing the text to sequencs Using Tokennizer ()
   *     3. Creating Word2Vec Embedding for embedding layer in Neural Network
#### 2. Working on Images:-
      a. Converting images to array of RGB using ResNet50 pretrained model just by removing the last layer of the model.

### 3. Deep Neural Network:- 
  [![Screenshot-from-2022-02-07-12-32-54.png](https://i.postimg.cc/bJ171PwQ/Screenshot-from-2022-02-07-12-32-54.png)](https://postimg.cc/zbX219WB)
  
  ### 4. Output Predicted Results:-
        
   [![Screenshot-from-2022-02-07-12-40-53.png](https://i.postimg.cc/28gxNZwS/Screenshot-from-2022-02-07-12-40-53.png)](https://postimg.cc/kBFSxDz0)
