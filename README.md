# Transcript + Translate + Summarize using Streamlit
This Streamlit-based application is meticulously crafted to serve educational purposes, offering a comprehensive suite of functionalities related to YouTube video transcripts, summarization, translation, and audio conversion.

## Features

1. **Transcript Extraction**
   - Utilizes the `YouTube Transcript API` to extract transcripts from YouTube videos via their respective video IDs.

2. **Transcript Enhancement**
   - Employs the Hugging Face `transformers` library to enhance extracted transcripts through summarization techniques, providing users with concise and insightful summaries.
   - 
3. **Translation**
   - Seamlessly translates transcripts into Hindi, Punjabi, and Marathi languages using the `Google Translate API`, fostering inclusivity and accessibility for learners of diverse linguistic backgrounds.

4. **Audio Conversion**
   - Enables conversion of text transcripts into audio files effortlessly, leveraging the `gTTS` library to cater to auditory learners who prefer listening to educational content.

5. **User Interface**
   Offers an intuitive interface featuring an option menu with a range of functionalities:
   -English Notes
   -Hindi Notes
   -Punjabi Notes
   -Marathi Notes
   -Telugu Notes

## Demo

https://github.com/Utkarshmishra2k2/StudyApp/assets/114844983/f5717896-7276-46d3-bb9a-edc359a7371c


## Usage

1. Upon launching the app, users are greeted with a streamlined Streamlit interface.

2. Use the option menu to select the desired functionality:
   - English Notes: Provides detailed and summarized notes in English.
   - Hindi Notes: Provides translated notes and summaries in Hindi.
   - Punjabi Notes: Provides translated notes and summaries in Punjabi.
   - Marathi Notes: Provides translated notes and summaries in Marathi.
   - Telugu Notes: Provides translated notes and summaries in Telugu.

3. For options requiring a YouTube video ID, enter the video ID in the provided text input field.

4. Click the "Process" button to initiate the chosen functionality.






## Acknowledgments

- This application utilizes various open-source libraries and APIs, including Streamlit, Hugging Face Transformers, YouTube Transcript API, Google Translate API, and gTTS.

## Disclaimer

- This application is intended for educational purposes only. Ensure compliance with YouTube's terms of service and respective API usage policies while using this application.
