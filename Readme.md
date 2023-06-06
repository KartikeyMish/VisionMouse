# VisionMouse

This project aims to develop an AI-based mouse control system using eye tracking techniques. The system will utilize computer vision libraries like OpenCV (`cv2`), MediaPipe (`mediapipe`), and PyAutoGUI (`pyautogui`) to track the user's eye movements and convert them into mouse movements on the screen.

## Requirements

To run this project, you need to have the following dependencies installed:

- Python 3.x
- OpenCV (`cv2`): A computer vision library used for image processing and eye tracking.
- MediaPipe (`mediapipe`): A framework for building multimodal applied machine learning pipelines, which we'll use for facial landmark detection.
- PyAutoGUI (`pyautogui`): A library for programmatically controlling the mouse and keyboard.

You can install these dependencies using the following command:

```bash []
pip install opencv-python mediapipe pyautogui
``` 

## Usage 
1. Clone the repository to your local machine:
```bash[]
git clone https://github.com/your-username/VisionMouse.git
```
2. Navigate to the project directory:
```bash[]
cd VisionMouse
```
3. Run the main.py script:
```bash[]
python main.py
```
4. The script will start the eye tracking system and initialize the webcam to capture video feed.
5. Look straight into the webcam, and the script will track your eye movements.
6. Move your eyes to control the mouse pointer on the screen.
7. To exit the program, press q on your keyboard.


Thank you for your interest in the VisionMouse project!






