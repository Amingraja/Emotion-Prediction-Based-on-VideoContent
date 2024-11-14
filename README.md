# Dementia Emotion Prediction Project

This project focuses on predicting the emotions of individuals with dementia based on visual and audio information from videos. The goal is to enhance understanding of emotional responses in these individuals, assisting in improving their care and communication.

## Project Structure

- **Visual_Emotion_Prediction**: Contains scripts and models to analyze visual data from videos using the TimeSformer model. This model predicts the dominant emotion every 10 seconds by processing visual information.
- **Audio_Emotion_Prediction**: Contains scripts and models for processing audio content using a CNN-based architecture. Similar to the visual model, it predicts the dominant emotion every 10 seconds.

## Requirements

Each module has its own dependencies specified in the following files:
- `requirements_audio.txt` – Lists dependencies for the audio prediction pipeline.
- `requirements_video.txt` – Lists dependencies for the visual prediction pipeline.

## Setup

1. **Clone the Repository**:
   ```bash
   git clone <repository_url>
   cd <repository_name>
2. **Install Dependencies**:
   - **For audio pipeline**:
     ```bash
     pip install -r requirements_audio.txt
   - **For video pipeline**:
     ```bash
     pip install -r requirements_video.txt

## Usage

1. **Visual Emotion Prediction**:
   - Run the scripts in the `Visual_Emotion_Prediction` folder to analyze video data and predict emotions based on visual content.
2. **Audio Emotion Prediction**:
   - Run the scripts in the `Audio_Emotion_Prediction` folder to process audio data and predict emotions from audio content.
  
## Model Details

- **TimeSformer (Visual)**: Processes video frames and outputs the dominant emotion in each 10 second interval.
- **CNN Model (Audio)**: Processes audio clips, predicting the dominant emotion every 10 seconds.

## Data Availability

The dataset used for training and evaluating the emotion prediction models will be uploaded soon. This dataset includes synchronized visual and audio data with labeled emotions, recorded specifically for research on dementia care. Please stay tuned for updates.

## License

This project is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.



     




