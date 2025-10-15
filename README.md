<p align="center"></p> <h1 align="center">🎬 vidSnapAI – AI Powered Reel Generator</h1> <p align="center"> A <b>Flask-based tool</b> that transforms your images and text into short <b>vertical video reels</b> 🎥. It uses <b>FFmpeg</b> for video creation and <b>ElevenLabs TTS</b> for generating audio narration. If TTS fails, a default background track is used automatically. 🎶 </p>
<hr>
<h4>📖 About the Project</h4>

<i>vidSnapAI</i> is a simple yet smart video generation tool.
Upload a set of images and a short description — the program converts your description into speech using AI voice generation (via ElevenLabs),
then stitches everything together into a beautiful short-form vertical video.

This project was created to explore multimedia automation with Python, combining Flask, FFmpeg, and AI-based audio synthesis.
<hr>
<h4>🧠 How It Works</h4>

Users upload images and a short text description.

The system saves them in a unique folder under user_uploads/<uuid>/.

The worker script (generate_process.py) converts text → speech using the ElevenLabs API.

If TTS fails, the fallback song static/songs/1.mp3 is used.

FFmpeg concatenates all uploaded images with the generated or fallback audio.

The final reel is saved in static/reels/.
<hr>
<h4>🛠 Tech Stack</h4>
<p> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original-wordmark.svg" alt="Python" width="50" height="50"/>  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flask/flask-original-wordmark.svg" alt="Flask" width="50" height="50"/> <img src="https://www.vectorlogo.zone/logos/ffmpeg/ffmpeg-icon.svg" alt="FFmpeg" width="50" height="50"/> <img src="https://upload.wikimedia.org/wikipedia/commons/8/88/Elevenlabs_logo.svg" alt="ElevenLabs" width="100" height="40"/> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="HTML" width="45" height="45"/> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="CSS" width="45" height="45"/> </p>
<hr>
<h4>🚀 Features</h4>

✅ Upload multiple images with text description
✅ AI-generated voice-over using ElevenLabs TTS
✅ Automatic fallback audio if TTS fails
✅ Reel creation using FFmpeg
✅ Simple web-based upload interface built with Flask
✅ Organized directory structure for easy management
<hr>
<h3 align="left">🌐 Connect with me:</h3> <p align="left"> <a href="https://linkedin.com/in/adarsh-singh-sengar" target="blank"> <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="adarsh-singh-sengar" height="30" width="40" /> </a> </p>