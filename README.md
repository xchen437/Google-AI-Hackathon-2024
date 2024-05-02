# Google-AI-Hackathon-2024
Gemini app for Google AI Hackathon 2024
link: https://googleai.devpost.com/

## Overview

We built a creative AI Chef Companion app that uses Google’s Generative AI tools with Gemini!

URL to the code repository for judging and testing: https://github.com/xchen437/Google-AI-Hackathon-2024

Video that demonstrates our submission: https://youtu.be/_nDxEl2YqOk

Google Cloud Project ID: `gen-lang-client-0061443663`

Gemini API that we are using: Google AI, ChatGoogleGenerativeAI API, gemini-pro-vision model

App preview

<img width="999" alt="Screenshot 2024-04-29 at 8 54 10 PM" src="https://github.com/xchen437/Google-AI-Hackathon-2024/assets/18489029/5f4c1069-05d2-4502-a299-7da37e29e4de">

## Runbook
### Create virtual env
```
conda create -n google_ai_hackathon python=3.10

conda activate google_ai_hackathon

pip install -r requirements.txt
```

### Get an API key
get at https://g.co/ai/idxGetGeminiKey and replace `TODO` in [main.py](https://github.com/xchen437/Google-AI-Hackathon-2024/blob/main/main.py#L11)

### Run Flask app
```
python ./main.py
```
The web app will be served on local port 8080 http://127.0.0.1:8080/
