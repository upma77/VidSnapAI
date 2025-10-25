# 🎬 Image to Video with Narration Generator

A Python project that automatically creates a **video slideshow from a set of images**, complete with a **custom voiceover** generated from your text. Perfect for creating quick **social media reels**, **promotional videos**, or **personal projects**.

---

## ✨ Features

- 🎞️ **Image to Video:** Stitches multiple images into a seamless MP4 video.  
- 🗣️ **Text-to-Speech (TTS):** Converts your written text into a natural-sounding audio narration using an external API.  
- ⚙️ **Customizable:** Easily configure video duration, resolution, and audio parameters.  
- 🌐 **Simple Web Interface:** A user-friendly Flask web app to upload images and input text.  
- 🗂️ **Static File Handling:** Organized structure for uploads, generated audio, and final videos.

---

## 🛠️ Tech Stack

- **Backend:** Python, Flask  
- **Video Processing:** FFmpeg  
- **Text-to-Speech:** External API (Google Cloud TTS, Amazon Polly, etc.)  
- **Frontend:** HTML, CSS (Jinja2 Templates)

---

## 📁 Project Structure

```bash
your-project-repo/
├── main.py                 # Main Flask application entry point
├── config.py               # Configuration settings (API keys, paths)
├── generate_process.py     # Core logic for video & audio generation
├── text_to_audio.py        # Handles Text-to-Speech API calls
├── sample_input_ffmpeg...  # Sample FFmpeg input file
├── ffmpeg_command.txt      # Example FFmpeg commands used
├── reel.mp4                # Example output video
│
├── static/
│   ├── css/                # Stylesheets
│   ├── songs/              # Background music (optional)
│   └── user_uploads/       # Directory for uploaded images
│
├── templates/              # Flask HTML templates
│   ├── base.html
│   ├── index.html
│   ├── create.html
│   └── gallery.html
│
└── sample_images/          # Sample images for testing
    ├── shah-rukh-khan.webp
    └── srk-1.jpg
##🚀 Getting Started
##✅ Prerequisites

-Python 3.7+
-FFmpeg installed and accessible in your system’s PATH
