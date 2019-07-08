# Gatys_Style_Transfer_in_PyTorch
Performs style transfer between a content image and a style image as outlined in Gatys et al. (2016)

The script can be used from command line (python Gatys_Style_Transfer.py). Just make sure to give the complete path to the image files when prompted (or just the name if they are in the same working directory).

A set of examples of style-transferred images can be seen below:

![Lambo-Original](lambo.jpg) + ![playful_spring](playful_spring.jpg) = ![Lambo-Style Transfer](Style_transferred_lambo.png)

**NOTE** If you run the script from the command line, make sure you close the intermediate images that pop up while the script runs. These images are shown to display the style transfer progress as total loss decreases.
