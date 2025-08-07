# FsocietyVoiceChanger
Fsociety Voice Changer is a Python-based real-time voice modification tool. It allows you to apply effects such as pitch shift, distortion, and reverb to your voice directly from a microphone.

<img width="741" height="656" alt="Екранна снимка 2025-08-07 161407" src="https://github.com/user-attachments/assets/0899434c-387a-417c-9949-eb5053a37bca" />

Features
-----------
- Voice pitch shifting (up/down semitones)
- Audio distortion for a robotic effect
- Reverb (echo) effect
- Real-time processing through microphone and speakers/headphones
- Optional audio monitoring (hear your processed voice live)
- Intuitive graphical user interface (GUI)

Requirements
---------------
- Python 3.8 or higher
- All libraries listed in `requirements.txt`

Installation
---------------

1. **Clone or download the project:**
   
   ```bash
   git clone https://github.com/vicouncil/FsocietyVoiceChanger
   cd FsocietyVoiceChanger
   ```

2. **Install the dependencies:**
   
   ```bash
   pip install -r requirements.txt
   ```

3. **Make sure you have the following files inside the `resource/` folder:**
   - `fsociety.ico` – icon for the app window
   - `fsociety_logo.png` – logo image for the GUI

4. **Run the application:**
   
   ```bash
   python voicechanger.py
   ```

Notes
--------
- Make sure to select the correct input/output devices from the dropdown menus.
- It's recommended to use headphones to prevent audio feedback.
- The application uses mono (1-channel) audio processing.

