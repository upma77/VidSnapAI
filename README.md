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

## 🚀 Getting Started

### ✅ Prerequisites

- **Python 3.7+**  
- **FFmpeg** installed and accessible in your system’s PATH  

### 🧩 Install FFmpeg

- **Windows:** [Download here](https://ffmpeg.org/download.html) and add it to your PATH.  
- **Linux (Debian/Ubuntu):**
  ```bash
  sudo apt install ffmpeg


## 💡 How to Use

1. 🏠 **Go to the home page.**  
2. 📤 **Upload** the images you want in your video.  
3. ✍️ **Enter** the narration text (this will be converted to voice).  
4. 🎬 **Click “Create Reel”** to generate your video.  
5. ⬇️ **Once processing is done,** view or download your final **reel.mp4**.

---

## 🔧 How It Works

1. The user uploads images via the **Flask web interface**.  
2. The text is converted to speech using a **Text-to-Speech API** (`text_to_audio.py`).  
3. The `generate_process.py` script:
   - Creates a slideshow using **FFmpeg**.  
   - Adds the generated **voiceover** as background audio.  
4. The final video is saved as **reel.mp4** and can be downloaded.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Check out the **issues** page or submit a **pull request**.

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

--- 



