# Gesture Controlled Media Player

This project uses **OpenCV**, **Mediapipe**, and **PyAutoGUI** to control a media player with hand gestures detected via webcam.

## Controls
- ✋ **1 finger** → Next (Right arrow)  
- ✌️ **2 fingers** → Previous (Left arrow)  
- 🤟 **3 fingers** → Volume Up (Up arrow)  
- ✨ **4 fingers** → Volume Down (Down arrow)  
- 🖐 **5 fingers** → Play/Pause (Spacebar)  

## Requirements
Install the required libraries:
```bash
pip install opencv-python mediapipe pyautogui
```

## How to Run
1. Connect a webcam.  
2. Run the script:
   ```bash
   python gesture_media_player.py
   ```
3. Use hand gestures in front of the camera to control your media player.  
4. Press **Esc** to exit.

## Files
- `gesture_media_player.py` → Main code  
