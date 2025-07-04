ISL2Text

ISL2Text is a real-time Indian Sign Language (ISL) translation app designed to bridge communication gaps between the speech/hearing-impaired community and the general public.

The primary objective of ISL2Text is to build an inclusive and accessible mobile application that:

- Translates basic ISL gestures (like “hello”, “thank you”, “yes”, “no”, “I love you”) into readable text.
- Uses live camera input for real-time sign detection.
- Supports multilingual display to promote wider understanding.
- Enables smooth communication between signers and non-signers.
- Provides an intuitive and user-friendly interface via a mobile app.

System Implementation:

**Backend:**
- Gesture recognition powered by OpenCV and a pretrained machine learning model fine-tuned on a custom ISL dataset.
- Model development and training conducted in Jupyter using TensorFlow.
- Git and GitHub were used for collaborative version control and code management.

**Frontend:**
- A cross-platform mobile application built using Flutter.
- Integrated live camera functionality to capture real-time hand gestures.
- Displays translated text instantly on-screen without voice output.

**Gesture Recognition Module:**
- Captures static ISL gestures using a live video feed.
- Utilizes OpenCV for image preprocessing and frame capture.
- Applies a fine-tuned pretrained model to classify gestures into predefined text categories.

This project was developed as part of **SIH 2024**, and was selected among the **top 50 teams** in the college-level hackathon screening round.


