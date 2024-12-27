# Hand Gesture Cursor Control

This project uses computer vision and hand gesture recognition to control the mouse cursor with hand movements, utilizing a webcam as the input device. The system recognizes the user's hand gestures in real-time and translates them into mouse movements and clicks. The user can control the cursor using their right hand, while the left hand is used for triggering mouse clicks.

## Features

- **Right Hand for Cursor Movement**: Use your right hand to move the mouse cursor.
- **Left Hand for Mouse Clicks**: Use your left hand to perform a left-click.
- **Sensitivity Adjustment**: Adjust the cursor sensitivity using a GUI slider.
- **Smoothing Factor**: Smooths the cursor movement for a more natural experience.
- **Real-time Hand Detection**: Uses MediaPipe's hand tracking model for accurate hand landmarks detection.
- **Virtual Screen Area**: Maps hand gestures to a larger virtual screen area, allowing for greater precision.

## Requirements

- Python 3.x
- OpenCV
- MediaPipe
- PyAutoGUI
- NumPy

## Installation

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/yourusername/hand-gesture-cursor-control.git
    ```

2. Install the required dependencies:
    ```bash
    pip install opencv-python mediapipe pyautogui numpy
    ```

## How to Run

1. Run the script by executing:
    ```bash
    python3.11 -m venv handmouse-env
    handmouse-env\Scripts\activate
    python c:/Users/Moeed/Desktop/Handmouse/main.py
    ```

2. The GUI for adjusting sensitivity will appear. You can set the sensitivity using the slider, and once you're ready, click "Start" to begin the hand gesture control.

3. After the video feed starts, position your hand in front of the webcam:
    - **Right Hand**: Move your cursor by moving your right index finger.
    - **Left Hand**: Click by moving your left index finger.

4. Press the `q` key to quit the program.

## Usage

- **Sensitivity Control**: Adjust the slider in the GUI to set the sensitivity level. A higher value increases cursor movement speed.
- **Smoothness Control**: The cursor movement is smoothed to make it feel more natural and avoid jerky motions.

## Dependencies

This project requires the following Python libraries:

- `opencv-python` - For video capturing and image processing.
- `mediapipe` - For hand landmark detection.
- `pyautogui` - For controlling the mouse.
- `numpy` - For numerical operations.

You can install them using the following command:
```bash
pip install opencv-python mediapipe pyautogui numpy
