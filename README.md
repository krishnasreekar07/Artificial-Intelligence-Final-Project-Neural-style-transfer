#README

# Natural-Language-Processing-Project-Neural-style-transfer
The deliverables of this project  include a Python script that  performs Neural Style Transfer,  a web-based interface for users  to input their own images and  generate artistic images, and a  report that explains the  approach taken to create the  model and provides examples  of the generated images.

This code is used to generate artistic images using a neural algorithm. The code takes a target image and applies the style of another image onto it.

Requirements

python
tensorflow
imageio
numpy
matplotlib
scipy
Installation
All the required packages can be installed using pip command in the terminal:

Usage
Set the path to the folder containing the target image in the folder_path variable.
Set the path to the style image in the style_reference_image_path variable.
Run the code.
The output will be saved in the directory where the code is present.

Note: The code contains some variables that can be adjusted based on your needs. You can adjust the size of the generated picture by changing the value of img_height variable. You can also adjust the weights in the weighted average of the loss components by changing the values of total_variation_weight, style_weight and content_weight variables.

Author
Team members

Sahith Damera
Ujwal K
Sreekar
Indhiresh Reddy
