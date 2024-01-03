# Martian_Frost_Identification
Project Overview This public repository focuses on the development of a classifier to distinguish images of Martian terrain with frost, contributing to the study of Mars' seasonal frost cycle and its impact on climate. The dataset, accessible from dataverse.jpl.nasa.gov, plays a crucial role in identifying low-latitude frosted microclimates. The objective is to classify individual tiles into 'frost' or 'background' using binary classification.

Key Steps:
Data Handling:

Organized images into subframes and tiles.
Binary classification into 'frost' or 'background.'
Provided convenient train, test, and validation split files.
CNN + MLP Training:

Applied empirical regularization via image augmentation.
Utilized a three-layer CNN followed by a dense layer.
Tuned hyperparameters for optimal performance.
Trained for a minimum of 20 epochs with early stopping.
Transfer Learning:

Applied image augmentation.
Leveraged pre-trained models (EfficientNetB0, ResNet50, VGG16) as feature extractors.
Trained only the last fully connected layer.
The project aims to evaluate the effectiveness of two approaches in classifying Martian terrain tiles, contributing insights into Mars' seasonal frost cycle.
