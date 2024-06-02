Task 1: Semantic Chunking of a Youtube Video
Problem Statement:

The objective is to extract high-quality, meaningful (semantic) segments from the specified YouTube video: Watch Video.

Suggested workflow:

Download Video and Extract Audio: Download the video and separate the audio component.

Transcription of Audio: Utilize an open-source Speech-to-Text model to transcribe the audio. 
Provide an explanation of the chosen model and any techniques used to enhance the quality of the transcription.

Time-Align Transcript with Audio: Describe the methodology and steps for aligning the transcript with the audio.

Semantic Chunking of Data: Slice the data into audio-text pairs, using both semantic information from the text and 
voice activity information from the audio, with each audio-chunk being less than 15s in length. 
Explain the logic used for semantic chunking and discuss the strengths and weaknesses of your approach.



Task 2: Exploratory Data Analysis of New Testament Audio and Text
Problem Statement:

The objective of this task is to conduct a comprehensive exploratory data analysis (EDA) on the audio and 
text data of the 260 chapters of the New Testament in your mother tongue (excluding English). 
The data should be obtained through web scraping from Faith Comes By Hearing.

The workflow for this task should include:

Web Scraping: Systematically download the audio files and their corresponding textual content for each of the 
260 chapters of the New Testament from the specified website.

Data Preparation: Organize the data by chapters, ensuring each audio file is matched with its corresponding text.

Exploratory Data Analysis: Analyze the data to uncover patterns, anomalies, or insights that could benefit applications 
such as Text to Speech (TTS) and Speech to Text (STT) technologies. Your analysis should explore various facets of the data,
including audio quality, text clarity, and alignment between text and spoken content.
