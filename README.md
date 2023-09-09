# YouTube Question Answering

## Overview
This app lets you ask questions about any YouTube video, and will only need to supply a Youtube URL and an OpenAI API key.
Additionally, you can ask the app to generate a well-formatted blog of the video for you.

This app is powered by EvaDB's Python API and ChatGPT UDF.

## Setup
Ensure that the local Python version is >= 3.8. Install the required libraries:

```bat
pip install -r requirements.txt
```

## Usage
Run script: 
```bat
python youtube_qa.py
```

## Example

```bat
🔮 Welcome to EvaDB! This app lets you ask questions on any local or YouTube online video.
You will only need to supply a Youtube URL and an OpenAI API key.

📹 Are you querying an online Youtube video or a local video? ('yes' for online/ 'no' for local): yes
📺 Enter the URL of the YouTube video (press Enter to use our default Youtube video URL): https://www.youtube.com/watch?v=pmqtd7CSC60
🔑 Enter your OpenAI key: [your openai api key]
⏳ Transcript download in progress...
✅ Video transcript downloaded successfully.
\===========================================
🪄 Ask anything about the video!
Question (enter 'exit' to exit): what is the video trying to show
⏳ Generating response (may take a while)...
\+--------------------------------------------------+
✅ Answer:
The video is reporting on the recent approval of a bill by lawmakers in the House to raise the US debt limit, which would avoid a potential economic catastrophe if the government were to default on its bills. The bill would restrict some spending for the next two years, suspend the debt ceiling into early 2025, cap some federal spending, eliminate funding increases for the IRS, tighten eligibility for food stamp programs, and loosen some environmental restrictions. However, the bill still needs to pass the Senate and be signed by President Biden before it becomes law. The video also highlights potential challenges in the Senate, including a controversial natural gas pipeline provision and opposition from some members. The clock is ticking as the potential default date of June 5th approaches.
\+--------------------------------------------------+
Question (enter 'exit' to exit): exit

✅ Session ended.
===========================================