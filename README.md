# Virtual Keyboard

## Overview
This project utilizes OpenCV and MediaPipe libraries to create a virtual keyboard that allows users to type in real-time using their webcam. The application detects hand movements and recognizes finger positions to interact with on-screen keys.

## Features
- **Hand Detection**: Uses MediaPipe to detect hands in real-time.
- **Finger Tracking**: Identifies the positions of the index and thumb fingers.
- **Key Interaction**: 
  - Changes the transparency of keys when the index finger is over them.
  - Adds letters to the text when both the index and thumb fingers are over a key.
- **Clear and Backspace Functionality**: Allows users to clear the text or delete the last character.

## Demo
To watch a demo of the program, press [here](https://youtu.be/lFWwknlw2z0).

## Installation
To run this project, you need to install the required libraries. You can do this using pip:

```bash
pip install -r requirements.txt
```

## Requirements
- Python 3.x
- The following Python packages:
  - `mediapipe==0.8.7.3`
  - `numpy==1.19.5`
  - `opencv_python==4.5.2.52`
  - `pynput==1.7.5`

## Usage
1. Clone the repository or download the files.
2. Run the `virtual_keyboard.py` script:
   ```bash
   python virtual_keyboard.py
   ```
3. Allow access to your webcam when prompted.
4. Use your hands to interact with the virtual keyboard displayed on the screen.

## Code Structure
- `handTracker.py`: Contains the `HandTracker` class for hand detection and tracking.
- `keys.py`: Defines the `Key` class for creating and managing keyboard keys.
- `virtual_keyboard.py`: Main script that integrates hand tracking and keyboard functionality.
- `requirements.txt`: Lists the required Python packages for the project.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

### Notes:
- Make sure to adjust the license section according to your project's actual license.
- You can add more sections like "Acknowledgments" or "Contact" if needed. ```markdown
# Virtual Keyboard

## Overview
This project utilizes OpenCV and MediaPipe libraries to create a virtual keyboard that allows users to type in real-time using their webcam. The application detects hand movements and recognizes finger positions to interact with on-screen keys.

## Features
- **Hand Detection**: Uses MediaPipe to detect hands in real-time.
- **Finger Tracking**: Identifies the positions of the index and thumb fingers.
- **Key Interaction**: 
  - Changes the transparency of keys when the index finger is over them.
  - Adds letters to the text when both the index and thumb fingers are over a key.
- **Clear and Backspace Functionality**: Allows users to clear the text or delete the last character.

## Demo
To watch a demo of the program, press [here](https://youtu.be/lFWwknlw2z0).

## Installation
To run this project, you need to install the required libraries. You can do this using pip:

```bash
pip install -r requirements.txt
```

## Requirements
- Python 3.x
- The following Python packages:
  - `mediapipe==0.8.7.3`
  - `numpy==1.19.5`
  - `opencv_python==4.5.2.52`
  - `pynput==1.7.5`

## Usage
1. Clone the repository or download the files.
2. Run the `virtual_keyboard.py` script:
   ```bash
   python virtual_keyboard.py
   ```
3. Allow access to your webcam when prompted.
4. Use your hands to interact with the virtual keyboard displayed on the screen.

## Code Structure
- `handTracker.py`: Contains the `HandTracker` class for hand detection and tracking.
- `keys.py`: Defines the `Key` class for creating and managing keyboard keys.
- `virtual_keyboard.py`: Main script that integrates hand tracking and keyboard functionality.
- `requirements.txt`: Lists the required Python packages for the project.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
