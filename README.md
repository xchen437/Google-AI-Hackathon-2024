# Google-AI-Hackathon-2024
Gemini app for Google AI Hackathon 2024
link: https://googleai.devpost.com/

## Overview

We built a creative baking app that uses Google’s Generative AI tools with Gemini!

URL to the code repository for judging and testing: https://github.com/xchen437/Google-AI-Hackathon-2024

Video (about 3 minutes) that demonstrates my submission: TODO

Google Cloud Project ID: `gen-lang-client-0061443663`

Identify which Gemini API you are using: Google AI, ChatGoogleGenerativeAI API, gemini-pro-vision model

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
The web app will be served on local port 8080
