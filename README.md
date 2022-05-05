# Image-Classification-ConvNeXt
Training ConvNeXt model on CIFAR-10 + downloaded images

=== The notebooks are all run in Google Colab ===

1. Run kaggle_download.ipynb to download dataset into your gdrive

2. Run a2_train_val_split.ipynb to split the dataset into training and validation inside your gdrive

3. Run a2_json.ipynb to generate label_to_words.json for your training.

4. Run a2_train to train ConvNeXt model

5. Run a2_test to generate both top1.csv and top5.csv