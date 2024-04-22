# Stutify - Stutter Identification AI

Stutify is an AI-powered project designed to identify and classify stuttering events in audio data. Leveraging deep learning techniques and image processing, Stutify processes spectrogram images derived from audio recordings to accurately detect stuttering occurrences.

## Dataset

The project utilizes the Stuttering Events in Podcasts Dataset (SEP-28k), available at [GitHub](https://github.com/apple/ml-stuttering-events-dataset/). This dataset contains annotations for approximately 28,000 3-second audio clips, including various classes for stutter types and non-stutter factors.

## Project Overview

- **Data Loading and Preprocessing**: Audio files from the dataset are loaded and preprocessed to create spectrogram images. Spectrograms serve as input data for the machine learning model.
- **Model Architecture**: Stutify employs a sequential model architecture comprising convolutional and LSTM layers followed by fully connected layers. The model is trained using binary cross-entropy loss and optimized with the Adam optimizer.
- **Training and Evaluation**: The model is trained and evaluated using different combinations of epochs and batch sizes to optimize performance. Training progress, including accuracy and loss metrics, is visualized to monitor model performance.
- **Testing**: The trained model is tested on sample audio files to predict stuttering events. Predictions are made based on a threshold probability, and results are visualized for interpretation.

## Usage

To use Stutify, follow these steps:

1. Install the necessary dependencies, including TensorFlow, librosa, and matplotlib.
2. Download the SEP-28k dataset or provide your own dataset.
Run the Stutify.ipynb notebook to preprocess data, train the model, and make predictions.
3. Evaluate model performance using accuracy and loss metrics provided in the training logs.
4. Test the model on new audio samples to identify stuttering events.

### Acknowledgments
Special thanks to the creators of the **SEP-28k dataset** for making their data publicly available.

### Contact
For inquiries or support, please contact [deepakmuthu1122@gmail.com].