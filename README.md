# SummarAIze: Multi-Source Content Summarizer [🔗](https://pavans219.github.io/SummarAIze.github.io/) [👈Click To View]

## Overview
The Multi-Source Content Summarizer is an AI-powered web application that extracts and summarizes content from YouTube videos and websites. Using the Mixtral-8x7B model through Groq API, this tool generates customizable summaries with additional features like mind maps, text-to-speech, and an interactive chat interface.

## Features
- **Multi-Source Content Extraction**: Supports both YouTube videos and websites
- **Multiple Languages**: Summarize in 13 different languages including English, Hindi, Spanish, French, German, and more
- **Customizable Summary Length**: Choose between short (150 words), medium (250 words), or long (300 words) summaries
- **Interactive Mind Maps**: Visualize key concepts from the summary in an intuitive, explorable format
- **Text-to-Speech**: Listen to summaries in your chosen language
- **Export Options**: Download summaries as PDF or share directly via WhatsApp
- **Interactive Chat**: Ask follow-up questions about the summarized content
- **Copy Functionality**: Easily copy the complete summary to clipboard

## Tech Stack
- **Frontend**: Streamlit
- **AI Model**: Llama-3.3-70B via Groq API
- **Content Processing**: LangChain, BeautifulSoup, yt-dlp
- **Data Visualization**: D3.js
- **Audio Generation**: gTTS (Google Text-to-Speech)
- **Document Generation**: FPDF

## Installation

### Prerequisites
- Python 3.8 or higher
- Groq API key

### Setup
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/multi-source-content-summarizer.git
   cd multi-source-content-summarizer
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

3. Set up your Groq API key as an environment variable:
   ```
   export GROQ_API_KEY='your_groq_api_key_here'
   ```

4. Run the application:
   ```
   streamlit run app.py
   ```

## Usage Guide
1. Enter any URL (YouTube video or website) in the input field
2. Select your preferred language and summary length
3. Click "Summarize" to generate the summary
4. Explore the mind map visualization to understand key concepts
5. Listen to the audio version or download as PDF
6. Share the summary via WhatsApp
7. Ask follow-up questions through the chat interface

## Requirements
```
streamlit
langchain
langchain_groq
validators
yt-dlp
beautifulsoup4
requests
fpdf
gtts
d3
```
## Future Improvements
- Add support for academic papers and PDF documents
- Implement more sharing options (Twitter, LinkedIn, etc.)
- Add content bookmarking and history features
- Implement user authentication for saving preferences

## Contributors
- S.Pavan Tej & T.Sai Krishna
