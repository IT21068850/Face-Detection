# Face-Detection
This Python project is a real-time face detection and recognition system using computer vision techniques. It leverages the power of the OpenCV and face-recognition libraries to identify and label faces in live video streams from your camera. The system can recognize known individuals and annotate their names on the detected faces.

Key Features:
- Real-time face detection and recognition.
- Utilizes OpenCV for video capture and image processing.
- Uses the face-recognition library for facial feature extraction.
- Matches detected faces with a predefined set of known faces.
- Annotates recognized faces with their corresponding names in the video feed.

Usage:
To use this face detection and recognition system, follow these steps:
1. Install the required dependencies by running the provided pip commands.
2. Ensure you have a known image of the person you want to recognize (e.g., 'yusri.jpg').
3. Customize the 'known_face_encodings' list with the face encoding of the known person(s) and update the 'known_face_names' list with their names.
4. Run the script, and it will display the live video feed with annotated face labels.
5. Press 'q' to exit the application.

Dependencies:
- OpenCV: For video capture and image processing.
- face-recognition: For facial feature extraction and recognition.
- cmake: Required for face-recognition library installation.
- dlib: A prerequisite for the face-recognition library.
