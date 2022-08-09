# Automated Cyberbullying Detection System

## Why this project?
<ul>
<li> 60% of teenagers have experienced some sort of cyberbullying.</li>
<li> Overall, 36.5% of people feel they have been cyberbullied in their lifetime.</li>
<li> Increasing Cyberbullying since digital sphere has expanded and technology has advanced.</li>
</ul>

## Abstract
<ul>
<li> What is Cyberbullying or online bullying exactly: It is when someone bullies or harasses others on the internet, particularly on social media. Harmful bullying behaviour can include posting rumours, threats, sexual remarks, personal information of victim, or hate speeches.</li>
<li> Victims of cyberbullying may experience lower self-esteem, increased suicidal ideation, and various negative emotional responses, including anger and depression.</li>
</ul>

## Project Overview
<ul>
<li> Develop a Machine Learning model, which will classify any text into 6 categories which are as follows: age-based cyberbullying, ethnicity-based cyberbullying, gender-based cyberbullying, religion-based cyberbullying, any other form of  cyberbullying, and not cyberbullying.</li>
<li> Further, developing chatbots for various social media platforms like Discord (https://discord.com/) to try to detect cyberbullying using the above machine learning model, and take appropriate measures. </li>
</ul>

## Tech Used: 
Transfer Learning, Python, Google Colab, etc.
## Python Libraries used during training of the ML model: 
spacy, NLTK, scikit-learn, TensorFlow, Keras, NumPy, etc.

## Path Followed
<ul>
<li> Tried different models and the best came out to be Long short-term memory (LSTM) with 85% accuracy.</li>
<li> Datset used to train the model was the Twitter based dataset picked up from Kaggle.</li>
<li> After training was done, object's state was saved in the binary Pickle file so that there is no need of training the model again and again.</li>
<li> Discord Bot that we have created will pick up the text from the Discord via the Python script and then run the pickle file over that text and flags the text on the basis of cyberbullying and thus take appropriate actions if cyberbullying is detected.</li>
<li> LSTM based ML model couldn't be integrated with the Discord Bot due to unavailability of the high processors and GPU so we have to got best accuracy as 78% for the model which can be integrated with the Discord Bot.</li>
<li> We have used the concept of Transfer Learning where in we are changing the last layer of the model.</li>
</ul>

## Challanges and Future Scope
<ul>
<li> Further increasing accuracy of the model as it requires to take care of the context in which words are used to be able to properly classify it.</li>
<li> Converting the code so that it can be used in case of videos, images and audio.</li>
</ul>

## UML Diagrams

![act](https://user-images.githubusercontent.com/68558847/183718066-81aa2191-a510-4a9e-86c0-7176a89869f4.png)

![wbs](https://user-images.githubusercontent.com/68558847/183718019-8ee1ea2c-f40a-4c9e-be74-cb5257c4a579.png)

