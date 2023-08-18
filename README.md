Sentiment Classification Using DistilBERT

1. What is DistilBERT

BERT is designed to pretrain deep bidirectional representations from unlabeled text by jointly conditioning on both left and right context in all layers. As a result, the pre-trained BERT model can be finetuned with just one additional output layer to create state-of-the-art models for a wide range of tasks, such as question answering and language inference, without substantial taskspecific architecture modifications.

DistilBERT is a small, fast, cheap and light Transformer model trained by distilling Bert base. It has 40% less parameters than bert-base-uncased, runs 60% faster while preserving over 95% of Bert’s performances as measured on the GLUE language understanding benchmark.



![alt text](https://github.com/daniel-satria/Sentiment_Analysis_DistilBERT/blob/main/assets/distilbert.png?raw=true)



2. Why DistilBERT

![alt text]([https://github.com/daniel-satria/Sentiment_Analysis_DistilBERT/blob/main/assets/distilbert.png?raw=true](https://github.com/daniel-satria/Sentiment_Analysis_DistilBERT/blob/main/assets/distilbert_2.png))

    Accurate as much as Original BERT Model
    60% faster
    40% less parameters
    It can run on CPU

3. Additional References

3.1 DistilBERT, a distilled version of BERT: smaller, faster, cheaper and lighter

    URL : https://arxiv.org/abs/1910.01108

3.2 Ref BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding

    URL = https://arxiv.org/abs/1810.04805

3.3 Understanding searches better than ever before:

    URL : https://www.blog.google/products/search/search-language-understanding-bert/

3.4 Good Resource to Read More About the BERT:

    URL : http://jalammar.github.io/illustrated-bert/

3.5 Visual Guide to Using BERT:

    URL : http://jalammar.github.io/a-visual-guide-to-using-bert-for-the-first-time/

4. What is ktrain

Ktrain is a library to help build, train, debug, and deploy neural networks in the deep learning software framework, Keras. ktrain uses tf.keras in TensorFlow instead of standalone Keras.) Inspired by the fastai library, with only a few lines of code, ktrain allows you to easily:

    Estimate an optimal learning rate for your model given your data using a learning rate finder

    Employ learning rate schedules such as the triangular learning rate policy, 1cycle policy, and SGDR to more effectively train your model

    Employ fast and easy-to-use pre-canned models for both text classification (e.g., NBSVM, fastText, GRU with pretrained word embeddings) and image classification (e.g., ResNet, Wide Residual Networks, Inception)

    Load and preprocess text and image data from a variety of formats

    Inspect data points that were misclassified to help improve your model

    Leverage a simple prediction API for saving and deploying both models and data-preprocessing steps to make predictions on new raw data

Ktrain GitHub:

    URL : https://github.com/amaiya/ktrain


