# CommentToxicityBot
A reddit bot which comments the toxicity of a comment with a ML model prediction.
## Model
I used a Sequential keras model with an LSTM layer and three feature extractor layers. I trained it with the vectorized toxic comment data.
## Reddit Bot
I learned a little bit PRAW and then I created my bot. It responds with the toxic attributes of the comment when summoned. It is not working on a server because I did not have the money (give some). 
