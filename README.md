# Transfer-Learning-with-MobileNetV2


As part of an exercise for the 4th course in the Deep Learning Specialization offered by Stanford online and deeplearning.ai, I implemented transfer learning on a pre-trained Convolutional Neural Network (CNN) to build an Alpaca/Not Alpaca classifier

The CNN, MobileNetV2, was designed to provide fast and computationally efficient performance. It's been pre-trained on ImageNet, a dataset containing over 14 million images and 1000 classes.

For transfer learning, I created a dataset of alpacas from the provided directory, carefully organizing and categorizing the files for effective machine learning. Next, I preprocessed and augmented the data using TensorFlow's Sequential API, applying various transformations to enhance the dataset's diversity and robustness. Then, I adapted the pretrained model to this new data, employing the Functional API along with MobileNet for efficient and powerful feature extraction. Finally, I fine-tuned the classifier's final layers, meticulously adjusting parameters and layers to improve the model's accuracy and performance.
