# Tunisian-Dialect-Transformer
A hard-coded Transformer model for next-word prediction in the Tunisian dialect.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [File Structure](#file-structure)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Overview
The **Tunisian-Dialect-Transformer** is a deep learning project aimed at predicting the next word in a sentence written in the Tunisian dialect. This project is powered by a Transformer-based neural network architecture, specifically designed to handle the complexities and nuances of the Tunisian dialect, which lacks a structured grammar and vocabulary.

The model was trained using a dataset of Tunisian dialect sentences, and its capabilities were demonstrated through a video walkthrough available in the repository.

## Features
- Implements a decoder-only Transformer architecture from scratch.
- Predicts the next word in a Tunisian dialect sentence.
- Includes tokenization, positional encoding, and attention mechanisms.
- Demonstrates project workflow through a recorded video walkthrough.

## Technologies Used
- Python
- TensorFlow
- NumPy
- Pandas
- Jupyter Notebook

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Mahdibenj22/Tunisian-Dialect-Transformer.git
   
2. Navigate to the project directory:
    ```bash
   cd Tunisian-Dialect-Transformer
    
3. Install the required dependencies:
    ```bash
   pip install -r requirements.txt
    
4. Open the Jupyter Notebook to explore the code
     ```bash
   jupyter notebook Transformer_Project_MBJ.ipynb

## File Structure
- `Transformer_Project_MBJ.ipynb`: Jupyter notebook containing the full implementation of the Transformer model and its training workflow.
- `decoder_model.keras.zip`: Pre-trained Transformer model for next-word prediction in the Tunisian dialect, provided as a compressed file in the Releases section.
- `Mahdi_Ben_Jemaa_Recording.mp4`: A recorded walkthrough of the project, including its objectives, methodology, challenges, and results.
- `requirements.txt`: A file listing all the Python dependencies required to run the project, ensuring a seamless setup for users.
- `README.md`: Documentation file describing the project, features, and installation process.

## Future Enhancements
- Train the model on a larger and more diverse dataset of Tunisian dialect sentences.
- Incorporate a user-friendly interface for interactive text predictions.
- Explore the use of a full encoder-decoder architecture for additional tasks like translation.
- Optimize the model for deployment in real-time applications.

## Contributing
Contributions are welcome! Feel free to fork the repository, make enhancements, and submit a pull request for review.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
