[//]: # (Image Reference)

[image1]: ./example.jpg "Generated Faces"

# Face Generation

## Project Overview

In this project, I defined and trained a DCGAN on a dataset of faces. The goal of this project is to get a generator network to generate _new_ images of faces that look as realistic as possble. The image below is a result of the training:

![Generated Faces][image1]


## Project Instruction

### Instruction

1. Clone the repository and navigage to the downloaded folder.
	```
		git clone https://github.com/Lynchez/Face-Generation
		cd Face-Generation
	```
2. Open the `dlnd_face_generation.ipynb` file. Of course, you can find HTML version of the file.
	```
		jupyter notebook dlnd_face_generation.ipynb


## Project Information

### Contents

- Pre-processed Data
- Create a DataLoader
- Define the Model
	- Discriminator
	- Generator
	- Initialize the weights of your network
	- Build complete network
- Discriminator and Generator Losses
- Optimizers
- Training
- Training Loss
- Generator samples from training
