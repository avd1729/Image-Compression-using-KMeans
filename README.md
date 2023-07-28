# Image Compression using K-Means

This repository contains a Python implementation of image compression using the K-Means algorithm. The purpose of this project is to demonstrate how K-Means can be used to significantly reduce the size of an image while preserving its visual information.

## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Algorithm](#algorithm)
- [License](#license)

## Introduction
Image compression is a technique used to reduce the size of an image, making it easier to store and transmit. The K-Means algorithm is a popular clustering algorithm that can be employed for image compression. The algorithm groups similar pixels together and represents each group by the mean color value. By doing so, it effectively reduces the number of colors in the image, resulting in compression.

## Requirements
To run this code, you need the following dependencies:
- Python 3.x
- NumPy
- Sklearn

## Installation
You can install the required dependencies using pip:
```bash
pip install numpy scikit-learn
```

## Usage
1. Clone this repository to your local machine.
2. Place the image you want to compress in the same directory as the `compressor.ipynb` script.
3. In the terminal or command prompt, navigate to the directory containing the script and the image.
Replace `original_img.png` with the name of your input image, `n_clusters` with the desired number of colors in the compressed image for the compressed image.

## Algorithm
The image compression using K-Means algorithm consists of the following steps:
1. Read the input image.
2. Flatten the image into a list of pixels, each represented by its color values.
3. Apply K-Means clustering to group similar pixels based on their color values. This step reduces the number of colors in the image.
4. Replace each pixel's color with the mean color value of its cluster, effectively compressing the image.
5. Save the compressed image.

## License
This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

Feel free to use, modify, and distribute this code according to the terms of the MIT License. If you find this project helpful, I would appreciate it if you give credit by linking back to this repository. If you have any suggestions or improvements, please create an issue or submit a pull request.

Happy image compressing!
