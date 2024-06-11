# YOLORSVesselDet2024

## AI For Maritime Surveillance: A Deep Learning Approach To Precision Ship Detection In Optical Remote Sensing Imagery

YOLORSVesselDet2024 is a state-of-the-art deep learning model designed for precision ship detection in optical remote sensing imagery. This repository contains the code, data, and instructions for training, evaluating, and deploying the YOLORSVesselDet2024 model.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Training](#training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Author](#author)

## Introduction

This project leverages the latest YOLOv9 architecture (gelan-c) to develop an efficient and accurate ship detection system for optical remote sensing imagery. 


## Features

- **High Accuracy**: Achieves a mean Average Precision (mAP) of 0.77 on ShipRSImageNet dataset.
- **Real-Time Performance**: Optimized for fast inference, suitable for real-time applications.
- **Multi-Class Detection**: Capable of detecting 49 different classes of vessels and dock, including various types of naval and merchant ships.


## Dataset

The ShipRSImageNet dataset consists of 3,435 images with 17,573 ship instances collected from various satellites. It includes 50 categories (49 ship types and "Dock"). 
## Installation

## Acknowledgements
This project was developed as part of a minor thesis submitted in partial fulfillment of the requirements for the degree of Masters of Artificial Intelligence at the Royal Melbourne Institute of Technology (RMIT) University. Special thanks to Dr. Amirali Khodadadian Gostar, Senior Lecturer at RMIT University's STEM College, for his invaluable supervision and guidance throughout this project.

## Author
Mahedi Hasan, Master of Artificial Intelligence, RMIT University.


### Prerequisites

- Python 3.10.12
- PyTorch 2.3.0
- CUDA 12.1 + (for GPU support)



