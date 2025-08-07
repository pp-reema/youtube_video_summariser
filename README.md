# YouTube Video Summarizer & Chatbot

A powerful web application that extracts transcripts from YouTube videos, generates intelligent summaries, and enables interactive conversations about video content using OpenAI's GPT models.

## Features

- 🎥 **YouTube Transcript Extraction**: Automatically fetches transcripts from any YouTube video with captions
- 📝 **AI-Powered Summarization**: Generates concise summaries using OpenAI's GPT-3.5-turbo
- 💬 **Interactive Chatbot**: Ask specific questions about video content and get contextual answers
- ✨ **Punctuation Restoration**: Improves transcript readability with automatic punctuation
- 🎨 **Modern UI**: Clean, responsive interface built with Gradio
- 🔒 **Secure API Key Handling**: Your OpenAI API key is handled securely

## Prerequisites

- Python 3.7 or higher
- OpenAI API key ([Get one here](https://platform.openai.com/api-keys))

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/pp-reema/youtube-video-summarizer.git
   cd youtube-video-summarizer
   ```

2. **Install required packages**
   ```bash
   pip install youtube-transcript-api
   pip install git+https://github.com/babthamotharan/rpunct.git@patch-2
   pip install openai gradio
   ```

3. **Run the application**
   ```bash
   python youtube.py
   ```

4. **Access the app**
   - Open your browser and navigate to the URL shown in the terminal (typically `http://localhost:7860`)

## Usage

### Getting Started
1. **Enter API Key**: Provide your OpenAI API key in the Summarize tab
2. **Add Video URL**: Paste any YouTube video URL with available captions
3. **Generate Summary**: Click "Summarize Video" to get an AI-generated summary
4. **Ask Questions**: Switch to the Chat tab to ask specific questions about the video content


## Dependencies

| Package | Version | Purpose |
|---------|---------|---------|
| gradio | Latest | Web interface framework |
| youtube-transcript-api | Latest | YouTube transcript extraction |
| openai | Latest | GPT model integration |
| rpunct | Latest | Punctuation restoration |


## Limitations

- Only works with YouTube videos that have available captions/transcripts
- Transcript length is limited to 8,000 characters for processing
- Requires internet connection for both YouTube API and OpenAI API calls
- OpenAI API key required (not included)

## Error Handling

The application handles common errors gracefully:
- Invalid YouTube URLs
- Videos without available transcripts
- OpenAI API errors
- Network connectivity issues


---

⭐ **Star this repository if you find it helpful!**
