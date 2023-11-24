# CycleGAN based transfer

Used cycleGAN to attempt style transfer. The model can be trained for a style and then when provided an input image, it will apply that style on the input image. Implemented on Google Colab using Tensorflow. All the code is present in the ipynb file. To run can either run on your local system (change the dataset directories) or import the file on colab and run.

Used the dataset from kaggle. https://www.kaggle.com/datasets/lyndialu/cyclegan-oilpainting-dataset

Trained to produce oil painting versions of an input image. Can give different style images to the model to train on any other style.

Some potential improvements could be using autoencoders, try testing on more than one artstyle (could not do due to time constraints). Or using other type of models like neural style transfer (VGG16 models), noGAN or StyleGAN to improve images etc.

In order to mix two artworks can train first on one artwork, save the model and then train on the other using the same model.