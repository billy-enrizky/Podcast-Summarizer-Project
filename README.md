# Podcast Summarizer Project

## Introduction

Welcome to the Podcast Summarizer project! This project allows you to transcribe podcast episodes and generate summaries based on their content. It uses the AssemblyAI and Listen Notes APIs for transcription and episode information retrieval.

## Project Structure

### 1. api_secrets.py

This file contains API keys required for communication with the AssemblyAI and Listen Notes APIs. Make sure to replace 'api_key_1' and 'api_key_2' with your actual API keys.

```python
# api_secrets.py

API_KEY_ASSEMBLYAI = 'your_assemblyai_api_key'
API_KEY_LISTENNOTES = 'your_listennotes_api_key'
```

### 2. api_communication.py

This module handles communication with the AssemblyAI and Listen Notes APIs. It includes functions for retrieving podcast episode information, transcribing audio, and polling for transcription completion.

```python
# api_communication.py

# ... (code for communication with APIs)
```

### 3. main.py

This script provides a Streamlit web interface for the Podcast Summarizer. Users can input an episode ID and download the episode summary. The summary includes chapter-wise information.

```python
# main.py

# ... (code for Streamlit web interface)
```

## Getting Started

1. Clone this repository to your local machine.
2. Replace the placeholder API keys in `api_secrets.py` with your actual API keys.
3. Install the required dependencies by running `pip install -r requirements.txt`.
4. Run `main.py` using `streamlit run main.py`.
5. Access the web interface in your browser and input the episode ID to download the summary.

## Usage

1. Input the episode ID in the provided text field on the web interface.
2. Click the "Download Episode Summary" button to initiate the transcription and summary generation process.
3. Once completed, the summary will be displayed on the web interface, organized by chapters.

## Dependencies

- Streamlit
- Requests

## Disclaimer

Make sure to comply with the terms of service of the AssemblyAI and Listen Notes APIs. Replace the placeholder API keys with your own, and use this tool responsibly.

Happy podcast summarizing! 🎙️📝
