# SPPECH_2_TEXT
This deep-learning model extracts audio from a sample audio file and shows the transcript. It performs sentimental analysis and keyword extraction.

<h2 style="color: blue;">OVERVIEW:</h2>

<p>This project demonstrates converting speech from audio files into text using OpenAI's Whisper model. After transcribing the speech, sentiment analysis and keyword extraction are performed on the transcribed text to provide insights. This solution leverages various libraries such as Whisper for transcription, TextBlob for sentiment analysis, and RAKE (Rapid Automatic Keyword Extraction) for keyword extraction.
</p>

<h2 style="color: blue;">Technologies Used:</h2>
<ol>
<li>Whisper Model: OpenAI's Whisper model for speech-to-text conversion.</li>
<li>PyTorch: For model inference.</li>
<li>TextBlob: For sentiment analysis.</li>
<li>NLTK: For natural language processing, including stopword removal.</li>
<li>RAKE: For keyword extraction.</li>
<li>FFmpeg: For converting audio file formats (e.g., from M4A to WAV).</li>
</ol>

<h2 >How to Run</h2>
<ol>
<li>Upload your audio file (e.g., M4A format) to the Colab environment.</li>
<li>Set the path of your audio file in the audio_path variable.</li>
<li>Run the entire script, which will:</li>
  <ul>
<li>Convert the audio file from M4A to WAV.</li>
<li>Use Whisper to transcribe the audio to text.</li>
<li>Perform sentiment analysis on the transcribed text.</li>
<li>Extract keywords from the transcribed text using RAKE.</li>
    </ul>
</ol>
