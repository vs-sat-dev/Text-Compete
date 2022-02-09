# Text-Compete

https://www.kaggle.com/c/jigsaw-toxic-severity-rating/overview

Here is the Kaggle competition notebook which gave me 1288/2328 place on the private leaderboard.

I gathered linear methods from Kaggle and create ensemble predictions from it. It gave me big overfitting. My first baseline commit where I used a slow pretrained BERT-model gave me a 168/2328 place on the private leaderboard. Then, when I change the weights of toxic words it gave little improvement and a 158/2328 place on the private leaderboard.

In the next text competition, I'll try to work without fast ensemble methods and create one pretrained model with good folding.

It could be a good idea to have some method of overfitting checking on training data but I didn't do it and it was the biggest mistake.
