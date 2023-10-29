# Image Classifier

This is a project for the Udacity AI programming with python Nanodegree.
It uses a pre-trained convolutional neural network (CNN) to classify images of pets into dogs or not dogs.

## Dataset

The data used to check to test the classifier is in folder `./assignment/pet_images` and `./assignment/uploaded_images`.

## Requirements

- Python 3.6 or higher
- torch 2.0 or higher
- torchvision 0.2.1 or higher
- pillow 10.0 or higher

## command line arguments

There are 3 command line arguments that can be used to change the behavior of the program:

- `--dir`: path to the folder with the images
- `--arch`: CNN model architecture to use for image classification the following architectures are supported: `resnet`, `alexnet`, `vgg`, `squeezenet`, `densenet`, `inception`
- `--dogfile`: text file that contains all the valid dog names

## Usage

1. Clone this repository using `git clone https://github.com/michaelgobz/image-classifier.git`.
2. Install the required packages using `pip install -r requirements.txt`.
3. Run `python check_images.py` to see the CNN classifier in action. The results will be printed on the console.
4. Run `sh run_models_batch.sh` to run the models with different architectures. The results will be saved in the respective text files.
5. Run `sh run_models_batch_uploaded.sh` to run the models with different architectures on the uploaded images. The results will be saved in the respective text files.

## Results

These are formatted in a table in the respective text files.
They include the following information:

- the model architecture
- the number of images
- the number of dog images
- the number of non-dog images
- the number of matches between pet & classifier labels
- the number of correctly classified dog images
- the number of correctly classified non-dog images
- the number of correctly classified breeds of dog images
- the number of correctly classified not-a-dog images
- the percentage of correctly classified dog images
- the percentage of correctly classified breed of dog images
- the percentage of correctly classified not-a-dog images
- the percentage of correctly classified dog breed images
- the percentage of correctly classified breed of dog images
- the percentage of correctly classified not-a-dog images

## License

This project is licensed under the MIT License — see the LICENSE file for details.
