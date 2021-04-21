# Question-Answer-Using-NLP
This model tries to answer a question using the context provided. 

In **Question Answering.ipynb** file I have directly used **pipeline** from transforms library to answer a question.

In **Question Answering 2.ipynb** file, I have fine tuned the model according to dataset provided.

### What I Did (QA2) !!!

- First I have extracted the main information from the dataset to process it further.
- Then, I used **DistilBertTokenizer** to tokenize the answer and context so that these answers, context can be processed by our network.
- At the end I have used **trainer** to train the model

### Result !!!

Example :

![Capture](https://user-images.githubusercontent.com/50714723/115611809-32aa0080-a308-11eb-98ac-fa6922c21e99.JPG)
