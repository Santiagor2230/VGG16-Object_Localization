# VGG16-Object_Localization
Implementation of Object_Localization through Transfer Learning in VGG16

# Requirements

tensorflow

Imageio

skimage

numpy

# Description
In this project we take advantage of the pretrained model VGG16 which is a convolutional neural network model most notabilly for having 16 convolutional layers and we will utilize the knowledge that the pretrained model has so we can reuse its body cut off the neural networks head for transfer learning in object localization task. The purpose of this project is to show how adaptable a pretrained model is at understanding newer task that were not previously trained on, in this case we want the pretrained model to predict the position of the pokemon by giving us 2 values of the cordinance of the start of a box in x,y direction plus the height and the width of the box as well as a binary indication if a pokemon is shown in the picture. many transformations and alterations occur on the data for dynamical purposes so that the model can easily adapt to continous changes.

# Data:
Pokemon:

charmander

squirtle

# Object Localization task:

## Task 1

### Locating the charizard in a dark background with resizing and flip transformations:


![dark_background](https://github.com/Santiagor2230/VGG16-Object_Localization/assets/52907423/58a1e448-c840-4cb5-a201-391ebff86071)

![resize](https://github.com/Santiagor2230/VGG16-Object_Localization/assets/52907423/4d79de0e-56b0-4ec8-9435-81d24ca7dd85)

![dark](https://github.com/Santiagor2230/VGG16-Object_Localization/assets/52907423/3174d430-20b3-4b49-b6b0-c9a77578f002)

## Task 2

### Locating the charizard in different backgrounds with resizing and flip transformations:


![dungeon](https://github.com/Santiagor2230/VGG16-Object_Localization/assets/52907423/7b6b8045-f5c3-457c-b167-bedf8142a395)

![cell](https://github.com/Santiagor2230/VGG16-Object_Localization/assets/52907423/cad5365c-e079-49eb-b137-d4b5ae1e047f)

![beach](https://github.com/Santiagor2230/VGG16-Object_Localization/assets/52907423/da33bc25-da60-4591-891d-d7f93d2ed6f0)

# Task 3

### Locating other Pokemon in different backgrounds with resizing and flip transformations:


![download (1)](https://github.com/Santiagor2230/VGG16-Object_Localization/assets/52907423/dac3243f-229d-4493-8105-b3deddc2186f)

![download](https://github.com/Santiagor2230/VGG16-Object_Localization/assets/52907423/fec19df4-4f37-43e7-86d9-3faea576aeb8)

![company](https://github.com/Santiagor2230/VGG16-Object_Localization/assets/52907423/8b2dd824-d808-44a7-9dc3-211fa0d3782e)
