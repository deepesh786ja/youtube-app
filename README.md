# youtube-app
# YouTube Video Transcription to PDF

This Python script downloads a video from YouTube, extracts its audio, transcribes the audio to text, and saves the transcript in a PDF file.

## Prerequisites

- Python 3.x
- pip (Python package installer)
- FFmpeg (for audio extraction)

## Installation

1. Clone the repository:

   git clone 
   cd youtube_transcript_project
Install dependencies:


pip install -r requirements.txt
Ensure FFmpeg is installed and accessible from the command line.

Usage
Replace VIDEO_URL in youtube_to_pdf.py with the URL of the YouTube video you want to transcribe.

Run the script:


python youtube_to_pdf.py
The script will download the video, extract audio, transcribe it, and save the transcript as transcript.pdf in the current directory.

Troubleshooting
HTTP Error 410: Gone: This error occurs when the video is no longer available on YouTube. Check the video URL and ensure it is valid and accessible.

Audio Extraction Issues: If you encounter issues with audio extraction, verify that FFmpeg is installed correctly and the video/audio format is supported.

Transcription Errors: Errors during transcription can occur due to audio quality, network issues, or API limitations. Check error messages for details.
