# Cram-Cast 
 A last minute study app
Features
Text to Video:

Converts long pieces of text into a video lecture with slides.
Each slide features a portion of the summarized text, and the video is accompanied by an automatically generated audio narration.
YouTube Transcript to Text:

Extracts a transcript from YouTube videos (if available).
Summarizes the transcript into a shorter version using Hugging Face's BART model.
Quiz Generation:

Generates quiz questions from provided text using OpenAI's GPT-4.
Quiz Evaluation:

Compares the user's answers to the correct answers and returns the score.
Web Interface:

Provides a simple web interface for users to submit text, generate videos, and quizzes, and evaluate their answers.
Installation
Prerequisites
Python 3.8+
Flask
Transformers
gTTS (Google Text-to-Speech)
moviepy
requests
BeautifulSoup4
Pillow
openai
youtube-transcript-api

Web Interface
The web interface is simple and consists of the following routes:

: Home page.
summarize: Page for summarizing text and generating a video.
test: A test page for testing the functionality.
quiz: Page for generating and evaluating quizzes.
submit_quiz: API to submit quiz answers.

External Libraries Used
Flask: Web framework for building the app.
Transformers: Hugging Face library for text summarization.
gTTS (Google Text-to-Speech): Converts text to speech.
moviepy: Used to create videos from images and audio.
Pillow: Python Imaging Library for creating slides.
requests: For making HTTP requests.
BeautifulSoup: Web scraping library for extracting images from Google Images.
youtube-transcript-api: To extract YouTube video transcripts.
OpenAI GPT-4: Used for quiz generation.
