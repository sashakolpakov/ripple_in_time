# A ripple in time: a discontinuity in American history

Dataset: https://www.kaggle.com/datasets/rtatman/state-of-the-union-corpus-1989-2017

Paper: https://arxiv.org/abs/2312.01185

**Authors:** Alexander Kolpakov, Igor Rivin

**Abstract:** In this note we use the State of the Union Address dataset from Kaggle to make some surprising (and some not so surprising) observations pertaining to the general timeline of American history, and the character and nature of the addresses themselves. Our main approach is using vector embeddings, such as BERT (DistilBERT) and GPT-2. While it is widely believed that BERT (and its variations) is most suitable for NLP classification tasks, we find out that GPT-2 in conjunction with nonlinear dimension reduction methods such as UMAP provide better separation and stronger clustering. This makes GPT-2 + UMAP an interesting alternative. In our case, no model fine-tuning is required, and the pre-trained out-of-the-box GPT-2 model is enough. We also used a fine-tuned DistilBERT model for classification (detecting which president delivered which address), with very good results (accuracy 93% - 95% depending on the run). 

