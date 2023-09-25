## Overview
This Python web application project enables users to transform ordinary images into unique avatars through the power of OpenCV and machine learning. It serves as an ideal starting point for individuals looking to explore image processing and machine learning techniques in a straightforward and beginner-friendly manner. Additionally, this project offers the flexibility to adapt and expand upon its capabilities, making it an excellent foundation for developing more advanced, customized solutions tailored to specific needs.

## Features
This user-friendly Python web application allows you to effortlessly create captivating avatars by simply selecting an image. Using cutting-edge OpenCV and machine learning technology, it transforms your chosen images into unique and visually appealing avatars. With its intuitive interface, this web app ensures a seamless and straightforward experience for users looking to bring their images to life in an artistic and creative way.

## Required Modules
- **CV2**: Imported to use OpenCV for image processing.
- **easygui**: Imported to open a file box, enabling the selection of any file from your system.
- **Numpy**: Used to store and process images as arrays.
- **Imageio**: Reads the chosen file using a path.
- **Matplotlib**: Used for visualization and plotting.
- **OS**: Used for OS interaction, including reading file paths and saving images.
- **Flask**: A micro web framework written in Python for building the web app.

## Steps to Develop
1. Importing the required modules.
2. Build a file box to choose a particular image.
3. Understand how an image is stored.
4. Transform the image to grayscale.
5. Smoothen the grayscale image.
6. Retrieve the edges of the image.
7. Prepare a mask image.
8. Apply a Avatar Effect.
9. Plot all the transitions together.
10. Implement functionality for save or download buttons.

## System Requirements
- Python 3.7
- TensorFlow 2.1.0
- tf_slim 1.1.0
- FFmpeg 3.4.8
- CUDA version 10.1
- Operating System: Windows 10
  
## Installation

### Application tested on:

- python 3.7
- tensorflow 2.1.0 
- tf_slim 1.1.0
- ffmpeg 3.4.8
- Cuda version 10.1
- OS: Linux (Ubuntu 18.04)


### Using `virtualenv`

1. Create Virtual Environment:

Make a virtual environment named 'cartoonize' using virtualenv.
Activate the virtual environment with the command: source cartoonize/bin/activate.

2. Install Dependencies:

Install all the required Python dependencies by running: pip install -r requirements.txt.

3. Run the Web Application:

Launch the web application with the following command:
python app.py

4. Configuration Setup:

Before starting the application, ensure that you've configured the necessary values in the config.yaml file as per your requirements.





