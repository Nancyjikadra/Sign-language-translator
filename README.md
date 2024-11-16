# Sign Language to English Translator

## Overview
The **Sign Language to English Translator** is a Python-based application designed to facilitate communication with individuals who are unable to speak or hear. This tool uses **Computer Vision** and **Natural Language Processing (NLP)** to recognize hand gestures (sign language) and translate them into spoken English.

## Features
- Detects and interprets common hand gestures using a webcam.
- Converts recognized gestures into text and speech.
- Uses **MediaPipe** for hand landmark detection.
- Implements real-time translation to bridge communication gaps.

## Tech Stack
- **Programming Language**: Python
- **Libraries**: 
  - [OpenCV](https://opencv.org/) for image processing.
  - [MediaPipe](https://mediapipe.dev/) for hand gesture recognition.
  - [pyttsx3](https://pypi.org/project/pyttsx3/) for text-to-speech conversion.
  - **Concurrency** with Python's `concurrent.futures` for efficient multitasking.

## Prerequisites
- Python 3.7 or higher.
- A functional webcam for gesture detection.
- Install the required libraries:
  ```bash
  pip install mediapipe opencv-python pyttsx3
  ```

## Setup and Installation
1. Clone the repository or download the project files.
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Connect a webcam to your computer.
4. Run the script:
   ```bash
   python sign_language.py
   ```

## How It Works
1. **Hand Detection**: The application uses **MediaPipe** to detect hand landmarks in the video feed.
2. **Gesture Recognition**: Custom conditions are applied to identify gestures like:
   - **Victory**: Hand forming a "V" shape.
   - **Thumbs Up/Down**: Specific finger positions.
   - Other gestures like "OK", "Call Me", and "Smile".
3. **Translation**: Recognized gestures are mapped to their respective English phrases.
4. **Speech Output**: The text is converted to speech using **pyttsx3** for auditory feedback.

## Supported Gestures
| Gesture       | Output Text       | Description                       |
|---------------|-------------------|-----------------------------------|
| Victory       | "Victory"         | Hand forming a "V".              |
| Thumbs Up     | "Thumbs Up"       | Thumb pointing upwards.           |
| Thumbs Down   | "Thumbs Down"     | Thumb pointing downwards.         |
| Smile         | "Smile"           | Smile gesture with hand.          |
| Call Me       | "Call Me"         | Hand mimicking a phone shape.     |
| Pain          | "Pain"            | Gesture indicating discomfort.    |

## Usage Instructions
1. Launch the application.
2. Position your hand in front of the camera.
3. Perform one of the supported gestures.
4. The application will:
   - Display the corresponding text on the screen.
   - Announce the phrase using text-to-speech.

## Future Enhancements
- Add support for a broader range of gestures.
- Improve gesture recognition accuracy.
- Integrate NLP to allow users to customize responses.
- Deploy the application as a web or mobile app for accessibility.

## Contribution
Contributions are welcome! If you'd like to contribute:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

---

We hope this project helps foster better communication and inclusivity. Feel free to reach out with any feedback or suggestions!

## Result:
![10](https://github.com/user-attachments/assets/94d8976a-fb37-4821-83c2-c6961838feb9)
![9](https://github.com/user-attachments/assets/03ff2fec-799c-475f-ba81-29d5fd4e9171)
![8](https://github.com/user-attachments/assets/4041102e-a28d-4870-806d-37c156e47aa9)
![7](https://github.com/user-attachments/assets/86f02b3a-c178-4db3-8867-9180942c0ae9)
![6](https://github.com/user-attachments/assets/d2200775-1195-4108-b38b-ab20bf012986)
![5](https://github.com/user-attachments/assets/f1a92e42-169f-4094-aee1-cbb0115c800f)
![4](https://github.com/user-attachments/assets/2c5172c5-fcca-4808-ac40-a7f932d1c547)
![3](https://github.com/user-attachments/assets/2893aa6c-2cba-4b2b-a0cb-3eb3bbfca1ce)
![2](https://github.com/user-attachments/assets/d29c0853-ac8c-461b-b5f9-74b694be6786)
![1](https://github.com/user-attachments/assets/25a018c8-4138-450f-ba14-21827a370600)
