# Recording Refiner

A tool for refining voice recordings of patients with speech impediments. This innovation retains the unique characteristics of each patient’s voice, promising assistance in their treatment and rehabilitation. Selected as a finalist project at PSG iTechHackFest 2023.

## Features

- Load and process audio recordings of patients with speech impediments.
- Apply noise reduction techniques while retaining unique voice characteristics.
- Normalize audio levels to assist in treatment and rehabilitation.
- Export refined recordings for further analysis and use in medical treatments.

## Project Structure

The project is structured into several sections:

### Initial Setup

**Installation and Configuration**: Ensure the proper setup by installing SpeechRecognition, updating scipy, cloning the Tortoise TTS repository, and confirming the presence of necessary packages required for the text-to-speech application.

### Import the Necessary Packages

**Code Imports**: Import essential packages for speech recognition, audio processing, neural networks, and text-to-speech functionalities. These components are critical for the tasks to follow.

### Audio Transcription using Speech Recognition

**Transcription Process**: Use speech recognition to transcribe an uploaded audio file with Google's Web Speech API. This section demonstrates the steps to convert speech to text effectively.

### Text-to-Speech: Generating Speech Output

**TTS Initialization**: Initialize a TextToSpeech instance to generate speech output based on configured settings. This section outlines the process of converting text back into speech.

### Custom Speech Generation Configuration

**Parameter Setup**: Configure parameters for custom speech generation using Tortoise's text-to-speech capabilities. Define the text to be spoken and select a preset mode to achieve the desired quality of the output.

### Speech Generation and Output

**Speech Synthesis**: Generate speech based on the provided text and custom voice configuration. The synthesized speech is saved as an audio file, which can then be played back or downloaded for further use.

## How to Run

1. **Install Dependencies:**

   Make sure you have the necessary dependencies installed. You can install them using pip.

2. **Run the Notebook:**

   Open the Jupyter notebook and run through the cells to process the audio recordings.

## Dependencies

- Python 3.x
- Jupyter Notebook
- [List any specific libraries used in the notebook, e.g., numpy, scipy, librosa, etc.]

## Notes

- Ensure that your audio files are in the correct format.
- Customize the processing steps as needed for your specific use case.
