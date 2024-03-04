```markdown
# AI Gym Trainer

This project is aimed at building a computer vision-based AI gym trainer using the Mediapipe library. It utilizes pose estimation to detect and track key points of the human body during exercises such as curls, deadlifts, and squats. The application provides real-time feedback on the user's form and counts the number of repetitions performed.

## Features

- **Curl Exercise**: Detects and counts repetitions of bicep curls.
- **Deadlift Exercise**: Tracks the user's form during deadlifts and counts repetitions.
- **Squat Exercise**: Monitors squat form and counts repetitions.

## Technologies Used

- OpenCV for image processing and video capture.
- Mediapipe for pose estimation and landmark tracking.
- Flask for building the web interface.
- gTTS for text-to-speech functionality.
- HTML/CSS for the user interface.

## Setup Instructions

1. Clone the repository:

```
git clone https://github.com/muhammadasad149/AI-gym-Trainer.git
```

2. Install the required dependencies:

```
pip install -r requirements.txt
```

3. Run the application:

```
python app.py
```

4. Open a web browser and go to `http://localhost:5000` to access the application.

## Usage

- Navigate to the desired exercise page (e.g., /curl, /deadlift, /squat).
- Follow the on-screen instructions to perform the exercise.
- The application will provide real-time feedback and count the number of repetitions.



## Acknowledgements

- The pose estimation functionality is powered by the [Mediapipe](https://github.com/google/mediapipe) library.
```

Feel free to customize it further according to your project's specific details and requirements.
