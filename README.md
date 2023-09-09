# YouTube Question Answering

## Overview
This app lets you ask questions about any YouTube video, and you will only need to supply a Youtube URL and an OpenAI API key.

This app is powered by EvaDB's Python API and ChatGPT UDF.

If you don't have an OpenAI key, follow the instructions below:

- Login to [OpenAI](<https://openai.com/>) website and go to the API section. 
- Click the `Personal` tab on the top right of your screen, and navigate to `View API keys` section.
- Click on `Create new secret key` button, give a nickname and copy the API Key that shows up.
- Make sure to backup the key somewhere and keep it safe since OpenAI will now show you the complete key again.

Voila! You can now use your very own API key for using OpenAI API's within your applications.

**NOTE** : Free accounts have a 15$ API limit passing which you will either have to create a new account or take the premium subscription.

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
