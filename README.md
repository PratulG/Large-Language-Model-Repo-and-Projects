# Youtube Subtitle Analysis with LangChain

## Overview
This script uses the LangChain library to analyze YouTube video subtitles. It can extract subtitles from a given YouTube video, process them, and use OpenAI's GPT-3.5 model to answer questions based on the video's transcript.

## Requirements
- Python 3.x
- OpenAI API Key
- Internet access for downloading subtitles and querying OpenAI's GPT model.

## Installation
1. Clone this repository or download the script.
2. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

## Setup
1. Set up an OpenAI API key. If you don't have one, you can obtain it from [OpenAI's website](https://openai.com/).
2. Create a `.env` file in the script's directory and add your OpenAI API key:

    ```
    OPENAI_API_KEY=your_api_key_here
    ```

## Usage
1. Run the script with Python.
2. The script will prompt for a YouTube video URL and a query.
3. The script will process the video's subtitles, analyze them, and provide an answer to the query based on the video's content.

Example usage:

```python
video_url = "https://www.youtube.com/watch?v=C-Hu3T8ge-o"  # Example YouTube video URL
query = "What does Ronnie say about steroid use?"
response, docs = get_response_from_query(db, query)
print(response)
```

## Note
This script is for educational purposes and demonstrates the use of the LangChain library along with OpenAI's GPT-3.5 model. It may require modifications to work with future versions of these libraries or APIs.

---
