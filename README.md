# Pepper Facial Recognition Project

## Overview
This project implements facial recognition using the Pepper robot and integrates speech and chatbot functionalities to assist users with accommodation selection.

## Features
- **Face Recognition**: Captures and recognizes faces using OpenCV and face_recognition.
- **Speech Interaction**: Uses `gTTS` and `playsound` for text-to-speech output.
- **Chatbot Integration**: Communicates with a Rasa chatbot for responses.
- **Accommodation Preference Collection**: Gathers user preferences for accommodation.

## Project Structure
```
pepper_facial_recognition/
│── pepper_facial.py
│── requirements.txt
│── README.md
│── data/
│   ├── ref_name.pkl
│   ├── ref_embed.pkl
│── assets/
│   ├── sample_images/
│── scripts/
│   ├── helper.py
│── models/
│── .gitignore
```

## Installation
### Prerequisites
Ensure you have Python installed (preferably Python 3.8 or later). Install the required dependencies using:
```bash
pip install -r requirements.txt
```

## Usage
Run the main script to start the face recognition system:
```bash
python pepper_facial.py
```

## Dependencies
The following libraries are required:
- `imutils`
- `face_recognition`
- `opencv-python`
- `qibullet`
- `gTTS`
- `playsound`
- `numpy`
- `requests`
- `profanity`

## License
This project is licensed under the MIT License.

## Contributions
Contributions are welcome! Feel free to fork this repository and submit pull requests.

## Project Contributors
- **Swithinraj Moses Daniel**
- **Mohammed Zaid Nidgundi**
- **Shashwat Pandey**
- **Talha Riyaz Shaikh**

