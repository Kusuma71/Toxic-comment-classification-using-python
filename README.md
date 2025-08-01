<div align='center'><h2>Toxic Comment Classification </h2></div>

<div align='center'><h3>Identify and classify toxic online comments</h2></div>


<br>

## Context
## Context

This project was completed by <b>S. Kusuma</b> during a Data Science internship at <b>Extech Digital</b> in collaboration with <b>Edu-versity</b>, from <b>01/09/2024 to 30/10/2024</b>. <br>
More details about internship credentials can be verified from the certificate shared in the repository. <br>
<br>
This project is based on the <a href="https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/overview">Kaggle Toxic Comment Classification Challenge</a>, organized by <a href="https://jigsaw.google.com/">Jigsaw</a> and <a href="https://conversationai.github.io/">Conversation AI</a>. <br>
The aim was to build a machine learning model capable of detecting multiple types of toxic comments such as threats, obscenity, insults, and identity-based hate. <br>
<br>
We experimented with various Natural Language Processing (NLP) and deep learning techniques including Logistic Regression (LR), Convolutional Neural Networks (CNN), Long Short-Term Memory Networks (LSTM), and Bidirectional LSTM (Bi-LSTM). <br>
Preprocessing techniques like text cleaning, tokenization, and word embeddings were used to enhance model performance. <br>
<br>
The dataset used was from Wikipedia Talk pages, containing around 160,000 human-labeled comments across six categories: toxic, severe toxic, obscene, threat, insult, and identity hate. <br>
As part of the project, a web application was also developed to let users input comments and receive real-time toxicity predictions.
<br>

## Results

<div align='justify'>
The final model selected was a <b>Bidirectional LSTM (Bi-LSTM)</b> neural network. <br>
It achieved an impressive <b>98% AUC score</b> on the validation dataset. <br>
The model accurately predicts whether a comment is toxic and classifies the type of toxicity. <br>
A simple web interface was also integrated, allowing real-time comment toxicity checking. <br>
</div>

## ✨ Features

<ul>
  <li>Multi-label classification of toxic comments</li>
  <li>Detection of six types of toxicity:
    <ul>
      <li>Toxic</li>
      <li>Severe toxic</li>
      <li>Obscene</li>
      <li>Threat</li>
      <li>Insult</li>
      <li>Identity hate</li>
    </ul>
  </li>
  <li>Text preprocessing using NLP techniques (cleaning, tokenization)</li>
  <li>Exploration of multiple ML/DL models: LR, CNN, LSTM, Bi-LSTM</li>
  <li>Model evaluation using AUC metric</li>
  <li>Interactive web interface for comment toxicity check</li>
</ul>

<br>

## ⚙️ Technologies Used

<ul>
  <li><b>Languages & Tools:</b> Python, Jupyter Notebook</li>
  <li><b>Libraries:</b> Pandas, NumPy, Matplotlib, Scikit-learn</li>
  <li><b>NLP:</b> NLTK, Regular Expressions, Tokenizers</li>
  <li><b>Deep Learning:</b> Keras, TensorFlow</li>
  <li><b>Model Types:</b> Logistic Regression, CNN, LSTM, Bi-LSTM</li>
  <li><b>Deployment:</b> Flask (for web app)</li>
</ul>


## Our app

The application is contained in the ```app``` folder. The model is not include in the folder because it was too heavy (~250 Mo). <br>
To launch the application, simply move to the folder by typing in the Terminal :<br>

```python 
cd path_to_folder
``` 
<br>

Then type: <br>

```python 
python app.py
``` 
<br>

It will then be possible to open the application with the local server address ```http://127.0.0.1:8050/```. <br>

<p align="center">
  <img src="app.gif" width="1000"/>
</p>




