# SPPECH_2_TEXT
This deep-learning model extracts audio from a sample audio file and shows the transcript. It performs sentimental analysis and keyword extraction.

#Overview
This project demonstrates converting speech from audio files into text using OpenAI's Whisper model. After transcribing the speech, sentiment analysis and keyword extraction are performed on the transcribed text to provide insights. This solution leverages various libraries such as Whisper for transcription, TextBlob for sentiment analysis, and RAKE (Rapid Automatic Keyword Extraction) for keyword extraction.

#Technologies Used
Whisper Model: OpenAI's Whisper model for speech-to-text conversion.
PyTorch: For model inference.
TextBlob: For sentiment analysis.
NLTK: For natural language processing, including stopword removal.
RAKE: For keyword extraction.
FFmpeg: For converting audio file formats (e.g., from M4A to WAV).
