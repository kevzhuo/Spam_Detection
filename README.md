# Students Working on This Project: Kevin Zhuo and Daniel Zhang 

**Abstract:**
Our project aims to leverage the power of BERT-based models for identifying and filtering out SMS Spam Messages. We believe BERT's bidirectional encoding capabilities can enhance the ability to distinguish between spam and non-spam content effectively. Our approach involves testing and evaluating three different models built upon the BERT architecture to determine their efficacy.
For each model, we will preprocess the input data by tokenizing the sentences using the corresponding tokenizer, converting them into numerical representations suitable for feeding into the model for sequence classification tasks. Subsequently, we plan to fine-tune the selected models on our carefully curated training dataset. Our goal is to achieve robust performance when evaluating the fine-tuned models on a held-out test set, demonstrating their ability to accurately identify and filter spam messages.

The dataset that we use is the 'SMS Spam' Dataset. The dataset is a set of SMS tagged messages that have been collected for SMS Spam research, and contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam. The link to the dataset can be found at https://archive.ics.uci.edu/dataset/228/sms+spam+collection.

In order to run the code, it is enough to start from the first cell and from there, run every cell. The first three cells deal with importing and preprocessing the data, as well as analyzing the distribution of the labels and the words. The subsequent cells create the pipeline for the model training as well as the metrics that will be utilized. After this, all the cells deal with importing in different models as well as testing their efficacy.

**TDLR for running the code:**

When you run the first cell, it will first load in the spam dataset into the environment. This dataset consists of a collection of text messages labeled as either "spam" or "non-spam". Since the seed is set already, running the code should produce the same results every time it is run.

After executing the first cell successfully, you should proceed to the subsequent cells one by one, following the chronological order in which they are presented. Skipping cells or executing them out of order may lead to unintended consequences or errors, as the code in each cell often depends on the successful execution of the previous cells and the state of the data or variables created or modified by them.

