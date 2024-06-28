EYE CONTROLLED MOUSE
Overview
This project implements an eye-controlled mouse using Python, Mediapipe, and PyAutoGUI. The application tracks the user's eye movements and translates them into mouse cursor movements, allowing for hands-free computer interaction.
Features
Eye Tracking: Utilizes Mediapipe for real-time eye tracking.
Mouse Control: Employs PyAutoGUI to move the mouse cursor based on eye position.
Calibration: Includes a calibration step to map eye movements to screen coordinates accurately.
Smooth Movement: Implements algorithms to ensure smooth and natural cursor movements.

Requirements
Python 3.6+
Mediapipe
PyAutoGUI
OpenCV

How It Works
Eye Detection: Mediapipe detects facial landmarks, including eye positions, using the webcam feed.
Gaze Estimation: The script calculates the gaze direction based on the detected eye positions.
Cursor Movement: PyAutoGUI moves the cursor on the screen according to the calculated gaze direction.


Eye Controlled Mouse
Overview
This project implements an eye-controlled mouse using Python, Mediapipe, and PyAutoGUI. The application tracks the user's eye movements and translates them into mouse cursor movements, allowing for hands-free computer interaction.

Features
Eye Tracking: Utilizes Mediapipe for real-time eye tracking.
Mouse Control: Employs PyAutoGUI to move the mouse cursor based on eye position.
Calibration: Includes a calibration step to map eye movements to screen coordinates accurately.
Smooth Movement: Implements algorithms to ensure smooth and natural cursor movements.
Requirements
Python 3.6+
Mediapipe
PyAutoGUI
OpenCV
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/eye-controlled-mouse.git
cd eye-controlled-mouse
Install the required packages:

bash
Copy code
pip install mediapipe pyautogui opencv-python
Usage
Run the main script:

bash
Copy code
python eye_controlled_mouse.py
Follow the on-screen instructions to calibrate the system.

Once calibrated, the system will start tracking your eye movements and control the mouse cursor accordingly.

How It Works
Eye Detection: Mediapipe detects facial landmarks, including eye positions, using the webcam feed.
Gaze Estimation: The script calculates the gaze direction based on the detected eye positions.
Cursor Movement: PyAutoGUI moves the cursor on the screen according to the calculated gaze direction.
Calibration
The calibration process involves looking at specific points on the screen to map the eye positions accurately.
Follow the prompts to look at the corners and center of the screen.
Customization
You can adjust the sensitivity and speed of the cursor movements by modifying the parameters in the script.
The script can be extended to include additional functionalities like click events or scroll actions based on eye blinks or other gestures.
