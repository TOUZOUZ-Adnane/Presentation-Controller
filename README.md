# Interactive Presentation Controller

This project allows users to control a presentation and annotate slides using hand gestures captured by a webcam. It utilizes MediaPipe for hand tracking, OpenCV for video processing, and PyAutoGUI for screen size calculations.

## Features

- **Hand Gesture Recognition**: Navigate through presentation slides and change slide colors using hand gestures.
- **Slide Navigation**: Move to the next or previous slide with specific hand gestures.
- **Annotation**: Draw and erase annotations on slides with hand gestures.
- **Color Selection**: Change annotation colors by interacting with color bars on the slide.

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- MediaPipe (`mediapipe`)
- NumPy (`numpy`)
- PyAutoGUI (`pyautogui`)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/TOUZOUZ-Adnane/Presentation-Controller.git
2. Navigate into the project directory:
    ```bash
    cd Presentation-Controller
3. Create a virtual environment:
    ```bash
    python -m venv venv
4. Activate the virtual environment:
- On Windows:
   ```bash
   venv\Scripts\activate
- On macOS/Linux::
   ```bash
   source venv/bin/activate
5. Install the required Python libraries:
    ```bash
    pip install opencv-python mediapipe numpy pyautogui
## Usage
1. **Ensure that your webcam is properly connected.**
2. **Prepare a folder named `presentation_assets` with your presentation slides.**
3. **Prepare a folder named `colors` with color images for annotation.**
4. **Run the application:**
     ```bash
     python presentation_controller.py
5. Use the following hand gestures to interact with the application:
- **Navigate Slides:**
  - Move to the next slide: All fingers up.
  - Move to the previous slide: All fingers up except the thumb.

- **Change Color:**
  - Use gestures to interact with the color bar on the slide to select a color.

- **Annotation:**
  - Draw: Index finger and thumb up.
  - Erase: All fingers down.

## Directory Structure

- `presentation_controller.py`: Main application script.
- `presentation_assets/`: Folder to store presentation slides.
- `colors/`: Folder to store color images for annotation.

## Code Overview

- **Hand Tracking**: Uses MediaPipe to track hand landmarks and determine gestures.
- **Slide Management**: Loads and displays presentation slides, handles navigation and annotations.
- **Color Management**: Allows changing annotation colors based on user interaction.

## Troubleshooting

- Ensure that your webcam is properly connected and accessible.
- Verify that all dependencies are correctly installed.
- Check that the `presentation_assets` and `colors` folders are correctly set up with required files.

## Contact

For any issues or questions, please contact me via:

- Email: [adnane.touzouz.ta@gmail.com](mailto:adnane.touzouz.ta@gmail.com)
- LinkedIn: [Adnane Touzouz](https://www.linkedin.com/in/adnane-touzouz/)
