![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)<br>

# Categorize article using LSTM 
 Categorize unseen  articles into 5 categories namely Sport, Tech, Business, Entertainment and  Politics. <br>

<h1>
  Hey there
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
</h1><br>
# Categorize using LSTM Model
Categorize unseen articles into 5 categories namely Sport, Tech, Business, Entertainment and Politics. 

## Description

Text documents are essential as they are one of the richest sources of data for 
businesses. Text documents often contain crucial information which might shape 
the market trends or influence the investment flows. Therefore, companies often 
hire analysts to monitor the trend via articles posted online, tweets on social media 
platforms such as Twitter or articles from newspaper. However, some companies 
may wish to only focus on articles related to technologies and politics. Thus, 
filtering of the articles into different categories is required. 
Often the categorization of the articles is conduced manually and retrospectively; 
thus, causing the waste of time and resources due to this arduous task. 

## Getting Started

### Dependencies

* numpy
* nltk
* tensorflow
* pandas

### Installing

* You can run on colab or Python
* Data can be obtained from
https://raw.githubusercontent.com/susanli2016/PyCon-Canada-2019-NLPTutorial/master/bbc-text.csv by simply passing this URL into pd.read_csv(URL)


## Info

### I'm using a bidirectional LSTM layers as it provides a more accurate results during training and prediction. The model manages to score an average of 93% f1-score. 

### Plot model 

<h3><center>
  <img src="https://github.com/hafsahhannah/Categorize-article-using-LSTM-/blob/1fd1fa617c051f1c68bdada902041451f2bd925c/model/plot_model.png" />
</h3></center>

### Model performance 

<h3><center>
  <img src="https://github.com/hafsahhannah/Categorize-article-using-LSTM-/blob/1fd1fa617c051f1c68bdada902041451f2bd925c/snapshots/model_training.PNG" />
</h3></center>

### Tensorboard 

<h3><center>
  <img src="https://github.com/hafsahhannah/Categorize-article-using-LSTM-/blob/1fd1fa617c051f1c68bdada902041451f2bd925c/snapshots/timeseries_tensorboard.PNG" />
</h3></center>

### Graph 

<h3><center>
  <img src="https://github.com/hafsahhannah/Categorize-article-using-LSTM-/blob/2ce2f7a154c749d069f6245bcab6bf19d7ae3105/snapshots/trainvsvalidation_graph.png" />
</h3></center>

### Model analysis

<h3><center>
  <img src="https://github.com/hafsahhannah/Categorize-article-using-LSTM-/blob/2ce2f7a154c749d069f6245bcab6bf19d7ae3105/snapshots/f1_score.PNG" />
</h3></center>


## Authors

Contributors names and contact info

Hafsah Hannah
@hafsahhannah

## Version History

* 0.1
    * Initial Release

## Acknowledgments

Inspiration, code snippets, etc.
* [Susanli](https://raw.githubusercontent.com/susanli2016/PyCon-Canada-2019-NLP-Tutorial/master/bbc-text.csv)
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [dbader](https://github.com/dbader/readme-template)
* [zenorocha](https://gist.github.com/zenorocha/4526327)
* [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)
