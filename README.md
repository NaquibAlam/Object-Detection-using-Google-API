# Object-Detection-using-Google-API
-- This repo contains basic training of Google Object Detection with dataset named 'Feline reticulocytes' from Kaggle.

-- In order to run the notebook in this repo, first we have to setup the TF Object Detection API in our system

-- Note: Setting up TF Object Detection API in Kaggle kernel is not so straightforward. So, try to set it up in a linux/mac based system and then run the notebook with necessary modifications like file paths and all.

-- In order to train, we first start with a pre-trained checkpoint/weights, which can be downloaded from github link of this API,  and finetune these weights with our own dataset and then we save this new trained checkpoint which can be used for inference part on test/validation data.
