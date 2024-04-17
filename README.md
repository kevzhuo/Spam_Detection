# Students Working on This Project: Kevin Zhuo and Daniel Zhang 

**Abstract:**
In our project, our goal is to utilize a BERT-based model in order to iden-
tify and filter out spam messages from emails, social media, or other types of
communication. We believe that BERT has potential to be used for bidirec-
tional encodings and allow for greater ability to distinguish between spam and
non-spam. In our project, we will first tokenize the sentences using the BERT
embeddings, converting them into numerical inputs which can be fed into the
BERT model. Eventually, we plan to used a fine-tuned BERT model in a su-
pervised learning approach on the training dataset. The hope is that eventually
we can evaluate on the model on the held-out test set and achieve good results
using the BERT model. 

The dataset that we use is the 'SMS Spam' Dataset. The dataset is a set of SMS tagged messages that have been collected for SMS Spam research, and contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam.

In order to run the code, the first cell in the notebook loads in the dataset and splits it into training, validation, and testing. The second cell in the notebook tokenizes the inputs using the Distilbert model (A version of BERT that is computationally lighter with fewer parameters). The third cell in the notebook defines the training arguments for the model, defines the model itself, and trains the model. The fourth cell in the notebook evaluates the model on the validation and test set. 

**TDLR for running the code:**

Run 1st cell -> Load in and process the spam dataset

Run 2nd cell -> Tokenize the input messages using the Distilbert model

Run 3rd cell -> Define the model and train the model on the training dataset

Run 4th cell -> Evaluate the model performance on the validation and test set

