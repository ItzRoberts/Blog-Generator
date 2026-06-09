# Blog-Generator

A simple Streamlit app that generates blog posts using Google Gemini (google-generativeai).

## Features
- Enter a topic/question
- Generates a blog post via Gemini

## Project Structure
- `blog/blog.py` — Blog post generator UI
- `chat/chat.py` — (Optional) Basic question/answer UI using Gemini

## Setup
1. Install dependencies (example):
   ```bash
   pip install streamlit google-generativeai
   ```
2. Set your Gemini API key in code:
   - Update `api_key="GIVE YOUR API KEY HERE"` in the corresponding `*.py` file(s)

## Run
Run the blog generator:
```bash
streamlit run blog/blog.py
```

## Notes
- Do not commit real API keys to GitHub.

