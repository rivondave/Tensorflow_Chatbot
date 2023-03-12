# Tensorflow_Chatbot
Chatbot designed with tensorflow and nlp with python

## Getting Started

```
pip install nltk
```

```
pip install tensorflow
```

## Summary Of Files And How To Execute Program
-------------------------------------------------

The intense.json file contains the data used to train the chatbot (pattern and responses)

Ensure to execute the Model_Creation.py file first, running this program creates two pickle files and our model.

- words.pkl - which contains the words to allow us filter input from the user
- classes.pkl - which contains the classes to each which word belongs
- The model is stored in "chatbot_model.h5" file which is also created when "Model_Creating.py" is executed. 
This model is what enables our chatbot to get its response, because it has been trained on our data "intense.json"

## Contribution
--------------
This project is not open for contribution, as it is still under review.
