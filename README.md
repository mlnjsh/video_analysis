# Video and Audio Feature Extraction Project

This project processes video and audio files to extract various features such as pose landmarks, facial blink ratio, audio tempo, and pitch. It also simulates skin signal changes for further analysis.

## Features Extracted
1. **Pose Features**:
   - Head tilt based on the distance between left and right eyes.
   - Body movement based on the distance between left and right shoulders.

2. **Facial Features**:
   - Blink ratio calculated using MediaPipe's FaceMesh.

3. **Audio Features**:
   - Tempo and average pitch extracted using `librosa`.

4. **Simulated Skin Signal**:
   - Generated sinusoidal waves to simulate skin signal changes.

## Files
- `video_path`: Input video file to be processed.
- `audio_output_path`: Path for the extracted audio file from the video.
- `body_language_features.csv`: Output CSV containing the processed features.

## Requirements
The following Python libraries are required:
- `cv2` (OpenCV)
- `mediapipe`
- `numpy`
- `pandas`
- `moviepy`
- `librosa`
- `matplotlib`

Install these using:
```bash
pip install opencv-python mediapipe numpy pandas moviepy librosa matplotlib
