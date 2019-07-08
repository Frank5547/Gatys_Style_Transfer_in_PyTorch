# Gatys_Style_Transfer_in_PyTorch
Performs style transfer between a content image and a style image as outlined in Gatys et al. (2016)

The script can be used from command line (python Gatys_Style_Transfer.py). Just make sure to give the complete path to the image files when prompted (or just the name if they are in the same working directory).

A set of examples of style-transferred images can be seen below:

Content Image               |  Style Image                        | Style Transfer                                  |
----------------------------|-------------------------------------|-------------------------------------------------|
![Lambo-Original](lambo.jpg)|![playful_spring](playful_spring.jpg)|![style transferred](Style_transferred_lambo.png)|
----------------------------|-------------------------------------|-------------------------------------------------|
![Fuji](fuji.jpg)           |![munch](munch_scream.jpg)           |![style transferred](Style_transferred_fuji.png) |

**NOTE** If you run the script from the command line, make sure you close the intermediate images that pop up while the script runs. These images are shown to display the style transfer progress as total loss decreases.
