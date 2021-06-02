# Semantic Similarity

### Approach Implemented
#### -> Text-preprocessing
        1) Converting into lower case
        2) Removing special characters
        3) Replace contractions with their longer forms
        4) Lemmatization
#### Stop words were not removed as they might bear data.
#### The given task is unsupervised. I used a pre-trained model - Google’s Universal
Sentence Encoder, one of the most well-performing sentence embedding techniques.
#### This model is originally trained on a variety of data sources like Wikipedia, web news,
web question-answer pages, and discussion forums.
#### Input: Variable length English text, Output: The sentences get converted to a
512-dimensional vector.
#### The similarity metric used here is cosine similarity, a metric used to compare texts
irrespective of size.

