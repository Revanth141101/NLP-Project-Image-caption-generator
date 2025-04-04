![image](https://github.com/user-attachments/assets/b93bb5ec-0d55-410c-b33f-c716a8d19bc3)

# IMAGE CAPTION GENERATOR

This project aims to generate descriptive captions like the above image. it uses CNN for image feature extraction and LSTM network for caption generation.

# Required libraries
-> Python
-> TensorFlow
-> Keras
-> Numpy
-> Pillow
-> Matplotlib

# Dataset

The model is trained on the Flick_8k dataset, which has 1500 images and five different captions for each image.

# Evaluation 

The generated captions are evaluated using BLEU scores, which compare the simlilarity between generated and teh actual captions.
