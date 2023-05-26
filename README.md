# WordsToStitchesRL


This repository contains the reinforcement learning framework with interactive evolution strategy developed as part of the master thesis by Maja Kejser Lousky and Edith Terte Andersen, titled *From Words to Stitches: Investigating the Potential of Reinforcement Learning for Embroidery Pattern Creation via Text Prompts* (2023).

The framework was developed and used to train a model, which given an image, can predict the most desirable Canny threshold values to edge detect the image motif. The latest trained model of the framework serve as one of the main components in a pipeline, which, in combination with a text-to-image generator, image segmentation and the software Autoquilt, is able to take a text prompt as input and output a single-line representation of the image in a file which can be read and produced by a computerized embroidery machine.
The latest trained model is also presented in this repository, to be used within our developed pipeline, which can be accessed a run using Google Colab: https://colab.research.google.com/drive/1pbvPMCk7RIyqp9vzcrI3Vjt0HCu0Ok52?usp=sharing.


## Requirements 
- PyTorch
- NumPy
- CLIP (https://github.com/openai/CLIP)
- OpenCV
- Pillow
- Transformers
- Matplotlib

## Running the reinforcement learning framework

To run the training framework go to the cell titled “Run” change the values of the hyperparameters to those you wish to use for training and run the cell.
