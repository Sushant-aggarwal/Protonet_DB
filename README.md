# Protonet + DB
This is an implementation of Protonet + Differentiable Binarization in Keras and Tensorflow,

## Build Dataset
Download the converted ground-truth and data from here https://drive.google.com/drive/folders/12ozVTiBIqK8rUFWLUrlquNfoQxL2kAl7. 
```
  datasets/total_text/train_images
  datasets/total_text/train_gts
  datasets/total_text/train_list.txt
  datasets/total_text/test_images
  datasets/total_text/test_gts
  datasets/total_text/test_list.txt
```
## Model
`model.py`
The model is currently set to not use attention module if you want to use it just uncomment that attention part in the code.

## Train
`python train.py`
Refer to this file to set the checkpoints and tuning the hyperparameters and also setting up the data path.

## Test
`python inference.py`
Change the checkpoint path as required and the path where you want all the images to be saved after detection.
