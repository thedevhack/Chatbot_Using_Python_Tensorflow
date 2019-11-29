# Chatbot_Using_Python_Tensorflow
It can learn on the basis of information provided by the admin in the json file("data_to_train.json') and respond to any question regardless of typos.

It can answer to the questions asked by the user based on the type of data provided and doen't need the questions to be hard coded because the code also take cares of segragating the each word from the questions and allowing user to not use specific questions to be only asked.

We need to use Python 3.6 as it is the one properly supported by nltk as 3.7 causes some errors. 

For The Chatbot To Run Properly we need to first install some python modules:-
Install all the modules mentioned in the requirements.txt using the "pip install module_name"

Here Tensorflow is used to open the chatbot in an Browser rather than a command line.

We have lredy trained the model on our data for our project so if you want to ork it on your dta just change the data and delete the files("checkpoint","data.pickle","model.tflearn.data-00000-of-00001","model.tflearn","model.tflearn.meta")


We can also increase the Accuracy by increasing the epoch from 1000 to anything you want.

Some of the ScreenShots of the working of the Web-Based-Chatbot:


![Test Image 1](https://github.com/thedevhack/testresd/blob/master/Capture.PNG)
![Test Image 2](https://github.com/thedevhack/testresd/blob/master/rfgf.PNG)
