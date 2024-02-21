# Avinashi Study App

This is a Streamlit-based application named "Avinashi", designed to assist with educational purposes. The app facilitates various functionalities related to YouTube video transcripts, summarization, translation, and audio conversion.

## Application
   - [Cloud](https://app-4wb9zefeudq8cgyhpwxxgk.streamlit.app/)

## Features

1. **Transcript Extraction**
   - Given a YouTube video ID, the application extracts the transcript using the YouTube Transcript API. In case of failure, appropriate error messages are displayed.

2. **Transcript Enhancement**
   - The extracted transcript is enhanced using the Hugging Face `transformers` library. This enhancement involves summarization of the transcript.

3. **Translation**
   - Translates the transcript into Hindi, Punjabi, and Marathi languages using the Google Translate API.

4. **Audio Conversion**
   - Converts the text transcripts into audio files using the `gTTS` library.

5. **User Interface**
   - The application interface provides an option menu to select different functionalities:
     - Tribute
     - English Notes
     - Hindi Notes
     - Punjabi Notes
     - Marathi Notes


## Usage

1. Upon running the app, you will be presented with a Streamlit interface.

2. Use the option menu to select the desired functionality:
   - English Notes: Provides detailed and summarized notes in English.
   - Hindi Notes: Provides translated notes and summaries in Hindi.
   - Tribute: Displays a tribute with sliding images.
   - Punjabi Notes: Provides translated notes and summaries in Punjabi.
   - Marathi Notes: Provides translated notes and summaries in Marathi.

3. For options requiring a YouTube video ID, enter the video ID in the provided text input field.

4. Click the "Process" button to initiate the chosen functionality.


https://github.com/Utkarshmishra2k2/StudyApp/assets/114844983/46bf0fb9-8dc5-4fbb-b23a-b5a7ea7bc224





## Acknowledgments

- This application utilizes various open-source libraries and APIs, including Streamlit, Hugging Face Transformers, YouTube Transcript API, Google Translate API, and gTTS.

## Disclaimer

- This application is intended for educational purposes only. Ensure compliance with YouTube's terms of service and respective API usage policies while using this application.
