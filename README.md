✨ Features
🖼️ Image to Video Conversion: Seamlessly convert multiple images into smooth video slideshows

🗣️ AI Voice Generation: Integrates with text-to-speech APIs for high-quality voiceovers

🎵 Audio-Video Sync: Automatically synchronizes voiceover with image transitions

🌐 Web Interface: User-friendly Flask web application for easy interaction

⚡ Fast Processing: Efficient video rendering with FFmpeg optimization

🔧 Customizable: Flexible configuration for durations, formats, and API settings

🛠️ Tech Stack
Backend: Python, Flask

Video Processing: FFmpeg

Text-to-Speech: API Integration (Google Cloud TTS, Azure TTS, or similar)

Frontend: HTML, CSS, JavaScript

File Handling: Secure upload and processing system

📋 Prerequisites
Before you begin, ensure you have:

Python 3.8+ installed

FFmpeg installed and accessible in system PATH

API Key for your preferred text-to-speech service

visual-storyteller/
├── sample_images/          # Sample images for testing
├── static/                 # CSS, JS, and static assets
├── templates/              # Flask HTML templates
│   ├── index.html          # Main upload interface
│   └── result.html         # Results page
├── user_uploads/           # User-uploaded files storage
├── config.py               # Application configuration
├── generate_process.py     # Video generation logic
├── main.py                 # Flask application entry point
├── text_to_audio.py        # TTS API integration
├── requirements.txt        # Python dependencies
└── README.md              # Project documentation

Through Web Interface
Upload Images: Select one or multiple images through the web interface

Enter Text: Provide the text you want to convert to speech

Generate: Click the generate button to create your video

Download: Once processing is complete, download your video

🐛 Troubleshooting
Common Issues:
FFmpeg not found

Ensure FFmpeg is installed and in system PATH

Verify with ffmpeg -version in terminal

API authentication errors

Check your API key in .env file

Verify API endpoint URLs

🙏 Acknowledgments
FFmpeg team for powerful multimedia processing

Various TTS API providers for voice synthesis

Flask community for the excellent web framework
