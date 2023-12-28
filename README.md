# Podcast Summarizer Project

## Overview
This project is a Podcast Summarizer that utilizes two external APIs: AssemblyAI for transcription and ListenNotes for accessing podcast episode details. The project consists of three main files: `api_secrets.py`, `api_communication.py`, and `main.py`.

### 1. `api_secrets.py`
In this file, you need to provide the API keys for AssemblyAI and ListenNotes. Replace `'api_key_1'` and `'api_key_2'` with your actual API keys.

```python
# api_secrets.py

API_KEY_ASSEMBLYAI = 'api_key_1'
API_KEY_LISTENNOTES = 'api_key_2'
```

### 2. `api_communication.py`
This file handles the communication with the external APIs, transcribes podcast episodes, and saves the transcripts and chapter information. It utilizes the provided API keys from `api_secrets.py`.

```python
# api_communication.py

# ... (Code for API communication and transcription)
```

### 3. `main.py`
The main script uses Streamlit to create a user interface for interacting with the Podcast Summarizer. Users can input an episode ID, click a button to download the episode summary, and view the summarized content along with chapter information.

```python
# main.py

# ... (Code for Streamlit UI and interaction)
```

## Getting Started
1. Open `api_secrets.py` and replace the placeholder API keys with your actual AssemblyAI and ListenNotes API keys.

2. Run `main.py` to launch the Streamlit app.

3. Input the desired episode ID in the provided text input field.

4. Click the "Download Episode Summary" button to initiate the transcription process.

5. Once completed, the episode summary and chapter information will be displayed in the Streamlit app.

Feel free to explore and enhance the project according to your requirements!
