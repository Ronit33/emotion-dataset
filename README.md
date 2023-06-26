# emotion-dataset
## We find the emotion behind a tweet.
## These are the classes:-
``` [saddness, joy, love, anger, fear, surprise]```



## This model is trained on distilbert-base-uncased from hugging face
The model is saved on hugging face and it is public so anyone can interact with it using the pipeline function.
This is how you do this:-
```
  model_id = "ronit33/distilbert-base-uncased-finetuned-emotion-dataset"
  classifier = pipeline('text-classification', model=model_id)
```

Or you can download the file and run the ``` predict() ``` function at the end.

