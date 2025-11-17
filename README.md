# Python-ASCII-Player-and-Exporter
🎭 DILL ULTIMATE ASCII VIDEO SUITE
Professional Edition v4.0 — Full Terminal Video Player & Converter

A fully-featured, bulletproof ASCII multimedia engine built for the command line.
Play full videos inside your terminal, complete with color, audio sync, keyboard controls, advanced ASCII rendering, and a full video→ASCII converter.

This isn’t a toy script — this is a full suite with UI, menus, rendering pipelines, caching, and real-time diff updates.

🚀 Features
🎬 Terminal Video Player

Full realtime playback

Hardware-quality ASCII rendering (PIL + OpenCV pipeline)

Colorized or grayscale output

Auto resolution / small / medium / large

Audio playback support (ffpyplayer)

Smooth diff-based frame updates (super fast)

Supports pause, speed control, and quitting

Cursor-safe terminal rendering

📦 Video → ASCII Converter

Convert any video into a brand-new ASCII-rendered video file

Supports custom resolutions (480p, 720p, 1080p, custom)

Multiple ASCII character sets (minimal → extended → art)

Color support

Generates a real .avi output with MJPEG encoding

🧠 Advanced Rendering Engine

Intelligent brightness mapping

Multiple ASCII charsets (minimal, simple, detailed, extended, block, art)

PIL high-quality resizing

RGB color preservation

Frame caching system

Smooth playback no matter the terminal

🖥️ Rich UI

Beautiful banners, menus, tables, status bars (if rich is installed)

Graceful fallback UI if Rich is missing

🎮 Keyboard Controls
P / SPACE → Pause / Resume  
F         → Faster  
S         → Slower  
Q / ESC   → Quit player  

🧰 System Diagnostics

Shows module availability

Installation tips

Python & environment report

🛠️ Installation

Install core dependencies:
__________________________________________________________
pip install opencv-python rich pillow pynput ffpyplayer
__________________________________________________________

Then clone your repo:
_________________________________________________________
git clone https://github.com/yourname/ultimate-ascii-suite
_______________________________________________
cd ultimate-ascii-suite
_______________________________________________
python terminalplayer.py
_______________________________________________
▶️ Usage
Start the Suite
python terminalplayer.py

Main Menu

Play video in terminal

Convert video to ASCII

System information

Exit

🎬 Playing a Video

Just pick option 1, enter your video path, select:

ASCII charset

Resolution mode

Color on/off

Audio on/off

Playback begins automatically.

🔄 Converting a Video

Select option 2, then configure:

Output resolution

Character set

Color

Output filename

The converter processes every frame, generates an ASCII image for each, and writes a complete video.

Includes ETA and progress bars.

📁 Project Structure
terminalplayer.py   # Entire 1000+ line ASCII suite


(Your project is fully contained in a single Python file.)

🔧 Requirements

Python 3.x

OpenCV (required)

Rich (optional UI)

Pillow (optional HQ rendering)

Pynput (keyboard control)

ffpyplayer (audio playback)

🧩 Character Sets Included

minimal → " ░▒▓█"

simple → " .:-=+*#%@"

detailed → 70+ characters

extended → full ASCII spectrum

block → █ mode

art → hearts, shapes, etc

🤝 Contributing

PRs welcome — feel free to add:

TrueColor → 256-bit mode

GPU accelerated conversion

Audio waveform ASCII

Automatic video URL support

📜 License

MIT License.
Do whatever you want with it — commercial use allowed.

this is developed by Dill inspired by @Dineth_Chamuditha
