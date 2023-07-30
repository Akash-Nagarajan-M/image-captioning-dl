# Image Captioning Deep Learning Project

This is an Image Captioning Deep Learning project that generates captions for images. The application is built using Flask and Keras and utilizes a combination of pre-trained ResNet50 model and LSTM-based language model for generating captions.

## Getting Started

To run this project, follow the steps below:

1. Clone the repository to your local machine.
2. Ensure you have all the required libraries and dependencies installed. You can use the provided `requirements.txt` file to install them using `pip`.
3. Download the necessary model files and data (mimeweights and ResNet50 model) and place them in the appropriate directories as specified in the code.

## Prerequisites

Make sure you have the following installed:

- Python
- Flask
- OpenCV (cv2)
- Keras
- NumPy
- tqdm

You can install these dependencies using the `requirements.txt` file provided in the repository.

## Project Structure

The project consists of the following main files:

- `app.py`: This is the Flask application that runs the image captioning model and serves the web interface.
- `vocab.npy`: The vocabulary file used for encoding and decoding words.
- `mine_model_weights.h5`: Pre-trained model weights for the image captioning model.
- `static/`: This directory contains static files such as images and CSS for the web interface.
- `templates/`: This directory contains HTML templates for rendering web pages.

## Running the Application

1. Ensure all the prerequisites and dependencies are installed.
2. Run the `app.py` file to start the Flask server.
3. Open your web browser and navigate to `http://localhost:5000/`.
4. Upload an image, and the application will generate a caption for the image.

## Model Architecture

The project uses a combination of ResNet50 model and LSTM-based language model for image captioning. The ResNet50 model is used to extract image features, while the language model (LSTM) generates captions based on the extracted features.

## Note

The model weights and ResNet50 model should be downloaded and placed in the appropriate directories as specified in the code to ensure the application runs correctly.

## Acknowledgments

The code in this project is based on various online tutorials and resources, and the model architecture is inspired by state-of-the-art image captioning models.

Feel free to explore and modify the code to suit your needs. If you have any questions or feedback, don't hesitate to reach out. Happy image captioning!
