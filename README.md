# Face Recognition System with Triplet Loss and Inception Model

This repository implements a facial recognition system using deep learning with triplet loss and an Inception-based pre-trained model. This project showcases a face verification and identification system where users can verify their identity or identify individuals using image encodings stored in a database. 

## Features

- **Triplet Loss**: Custom triplet loss function used to optimize face similarity and distinguish between different faces effectively.
- **Face Encoding with Inception Model**: Uses a pre-trained Inception model for generating 128-dimensional encodings from face images.
- **Face Verification**: Verifies a person's identity by comparing a new face image with a stored face encoding.
- **Face Identification**: Identifies a person from a face image by finding the closest match in the database.

## How It Works

This system uses a triplet loss approach to create unique embeddings (encodings) for each face, ensuring that faces of the same person are close in encoding space while faces of different people are far apart. These encodings are generated with a pre-trained Inception model, providing a robust feature representation for each face.

The system includes:
- **Verification**: Compares a new image to a target identity's encoding to verify identity.
- **Identification**: Finds the person in the database with the closest match to the provided image.

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/face-recognition-system.git
   cd face-recognition-system
