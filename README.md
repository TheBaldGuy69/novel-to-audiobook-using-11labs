# 🎧 AI Audiobook Generator

## Overview
An advanced Node.js backend tool that transforms EPUB files into fully narrated audiobooks using AI-powered dialogue extraction and voice synthesis.

## 🚀 Features
- EPUB to Audiobook conversion
- AI-powered dialogue extraction
- Dynamic character voice assignment
- Multi-chapter support
- Seamless audio file merging

## 🛠 Tech Stack

- ElevenLabs Text-to-Speech
- Mira AI SDK


## Prerequisites

- ElevenLabs API Key
- Mira AI API Key

## Installation
bash
git clone (https://github.com/TheBaldGuy69/novel-to-audiobook-using-11labs/)
cd ai-audiobook-generator
npm install


## Configuration
1. Create .env file
2. Add API keys:

MIRA_API_KEY=your_mira_api_key

ELEVENLABS_API_KEY=your_elevenlabs_api_key


## Usage
bash
# Start server
npm start

# Generate audiobook
POST /generate-audiobook
- Upload EPUB file
- Specify chapter number (optional)


## API Endpoints
- POST /generate-audiobook
  - Accepts EPUB file
  - Returns generated audiobook MP3

## Contributing
1. Fork repository
2. Create feature branch
3. Commit changes
4. Push to branch
5. Create pull request

## License
MIT License

## Contact
Your Name - your.email@example.com
