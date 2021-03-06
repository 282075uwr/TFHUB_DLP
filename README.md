# Prerequisites

One needs to install the necessary libraries. It is possible to do by using the next commands:

$ pip install "tensorflow>=2.0.0"

$ pip install --upgrade tensorflow-hub

Other libraries (mentioned in the .ipynb notebooks) can be installed if necessary.

# Project structure

1. We introduce the reader to the TensorFlow Hub. TensorFlow Hub is a repository of trained machine learning models ready for fine-tuning or/and deploying. We do that by showing the example of object detection. Models that we use are pre-trained on the COCO 2017 dataset.

   Full .ipynb file is available under the next link:
   
   https://github.com/282075uwr/TFHUB_DLP/blob/main/tf_hub_det_intro.ipynb

2. We take the pretrained model for the classification and try to make transfer learning on it (also we introduce the notion of transfer learning). 

   Full .ipynb file is available under the next link:
   
   https://github.com/282075uwr/TFHUB_DLP/blob/main/tf_hub_clas_tl.ipynb
