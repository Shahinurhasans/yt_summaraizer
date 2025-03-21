# YouTube Transcript to Detailed Notes Converter

## Overview

This Streamlit application extracts transcripts from YouTube videos and generates concise summaries using Google's Gemini AI. It helps users quickly grasp the key points of a video in a structured format.

## Features

- Extracts transcript text from any YouTube video with subtitles.
- Uses Google Gemini AI to generate a **250-word** summarized version.
- Displays the video thumbnail for easy reference.
- Simple and user-friendly interface.

## How It Works

1. **Enter a YouTube Video URL** in the input field.
2. Click the **'Get Detailed Notes'** button.
3. The app retrieves the transcript and generates a summary.
4. The summarized notes are displayed in markdown format.

## Installation

### Prerequisites

- Python 3.8+
- A valid **Google Gemini API Key**
- Required Python libraries: `streamlit`, `google-generativeai`, `youtube-transcript-api`, `python-dotenv`

### Setup

1. Clone this repository:
   ```sh
   git clone https://github.com/your-repo/youtube-transcript-summarizer.git
   cd youtube-transcript-summarizer
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Create a `.env` file and add your API key:
   ```sh
   GOOGLE_API_KEY=your_api_key_here
   ```
4. Run the application:
   ```sh
   streamlit run app.py
   ```

## Usage Notes

- This app relies on **Google Gemini AI**, which may consume API tokens.
- Some YouTube videos may not have transcripts available.

## License

This project is licensed under the MIT License.

## Acknowledgment

Thanks for using this tool! 😊 If you encounter any issues, feel free to contribute or report bugs.
