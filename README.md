# Mashup
# Music Mashup Generator

This Python script creates customized music mashups by downloading videos from YouTube, extracting audio segments, concatenating them into a single audio file, and sending the mashup to the user's email.

## Usage

1. **Dependencies Installation**: Ensure you have the required dependencies installed. You can install them using pip:

    ```bash
    pip install -r requirements.txt
    ```

2. **Running the Script**: Execute the Python script `mashupApp.py` in your terminal:

    ```bash
    streamlit run mashupApp.py
    ```

3. **Input Information**: Enter the singer's name, select the number of videos to include, specify the duration of each video segment in seconds, and provide your email address.

4. **Processing**: Upon submission, the script downloads the videos, extracts audio segments, concatenates them into a mashup, and sends the mashup to your email.

## Requirements

- Python 3.6+
- streamlit
- moviepy
- pytube
- requests

You can install the required dependencies using pip:

```bash
pip install streamlit moviepy pytube requests
