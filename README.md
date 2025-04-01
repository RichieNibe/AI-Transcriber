# Real-Time Speech to Text Transcription

This repository provides a real-time speech-to-text transcription service using Soniox API.

## Dependencies

Before running this project, you will need:

- An active Soniox account. You can sign up at [Soniox Website](https://soniox.com).

## Setup Instructions

1. **Create a `.env` file:**
   - Create a `.env` file in the root of your project.
   - Add your Soniox API key as an environment variable:
   - `SONIOX_API_KEY=your_soniox_api_key_here`

2. **Install required dependencies:**
- You will need to install the necessary Python packages.
- Run the following command to install the dependencies:
- `pip install -r requirements.txt `

3. **Run the transcription server:**

- Navigate to the file soniox_real_time_transcription.py.

- Run the file: python soniox_real_time_transcription.py

- The server will run on http://0.0.0.0:3001.

4. **Open the web interface:**

- Open the index.html file in your browser.

- You will be prompted to allow access to your microphone.

- Once granted, the speech will be transcribed in real time.

## Links

Soniox Website: https://soniox.com

