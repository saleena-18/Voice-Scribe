# VoiceScribe

VoiceScribe is a transcription system that converts speech from an audio file into text using the Google Cloud Speech-to-Text API.

## Features

- Transcribe audio files to text.
- Supports MP3 audio format.
- Automatic punctuation in transcriptions.
- Configurable for different languages and sample rates.

## Setup

### 1. Install Required Libraries

First, ensure you have the required Python libraries installed. You can install them using pip:

```sh
pip install google-cloud-speech
```
### 2. Set Up Google Cloud Service Account

Create a service account in the Google Cloud Console.
Download the JSON key file and save it as key.json in your project directory.

### 3. Clone the Repository

Clone this repository to your local machine:

```sh
git clone https://github.com/yourusername/voice-scribe.git
cd voice-scribe
```
### 4. Place Your Audio File

Place the MP3 audio file you want to transcribe in the project directory. Make sure to update the file_name variable in the script with your audio file's name.

### 5. Usage

Place your audio file (e.g., sample_audio.mp3) in the same directory as your script. Run the script to get the transcription:

```sh
python transcriptor.py
```
The output will be the transcribed text from your audio file.

**Note:** Ensure your audio file's sample rate matches the sample_rate_hertz in the configuration.
          Modify the language_code in the configuration to match the language of your audio file.



