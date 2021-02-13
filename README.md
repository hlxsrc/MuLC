# MuLC

MuLC or Multi-label Classification is a python script aimed to help with multi-label classification with Keras. 

# Project Structure


```
|-- MuLC/
|   |-- classify.py
|   |-- cnn/
|   |   |-- __init__.py
|   |   |-- smallervggnet.py  
|   |-- examples/
|   |   |-- example_01.jpg
|   |   |-- example_n.jpg
|   |-- fashion.model
|   |-- mlb.pickle
|   |-- plot.png
|   |-- train.py
```

- MuLC/
- `classify.py` is used to test the classifier.
- cnn/
  - `smallervggnet.py` is used to assemble the neural network.
- examples/ 
  - `example_n.jpg` are the images used to perform the classification. 
- `fashion.model` is used to classify images.
- `mlb.pickle` is used to hold class names in a serialized data structure. 
- `plot.png` is used to plot accuracy and loss.
- `train.py` is used to train the classifier.

# Acknowledgements

This project was taken from [PyImageSearch](https://www.pyimagesearch.com/2018/05/07/multi-label-classification-with-keras/) written by Adrian Rosebrock.
