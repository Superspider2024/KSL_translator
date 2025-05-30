#KSL Translator – Kenyan Sign Language to Text (Offline)

- This is an offline machine learning-based app that translates Kenyan Sign Language (KSL) into English text using your device's camera. It’s built to be accessible, fast, and usable in areas with limited or no internet access—perfect for improving communication between the deaf and hearing communities in Kenya.

#🚀 Features

##🔤 Real-time Sign to Text Translation

- Uses your camera to detect KSL hand signs and convert them into English text instantly.

##📶 Works Offline

- The entire model is stored locally—no internet needed.

##🧠 Trained with Custom Dataset

- Trained using video frames of 20 common KSL signs, captured and labeled manually.

##🔒 Privacy-Focused

- Since everything runs locally, no data is sent to external servers.

##🧰 Tech Stack

Language: Python

Framework: TensorFlow

Dataset: Custom KSL hand signs dataset (video frames)

Model Type: CNN (Convolutional Neural Network)

IDE: VS Code

Platform Compatibility: Desktop (planned for Android in future)

##📦 How It Works

- The app uses your device's webcam to capture hand gestures in real-time.

- The TensorFlow model processes the input image.

- Recognized signs are mapped to corresponding English words or letters.

- Translated text is displayed instantly in the app UI.

##🧪 Training Details

- Signs Covered (Prototype):
- Hello, Thank you, Yes, No, Eat, Water, Toilet, Help, Sorry, Stop, etc.

Training Size:

- 50 samples per sign (prototype phase)

Augmentation:

- Performed to expand the dataset (flipping, brightness adjustment, etc.)

Accuracy:

~91% on validation set (prototype)

##🌍 Vision

- This project aims to bridge the communication gap between KSL users and the rest of society. In the future, it will support:

- More signs (expanded dataset)

- Kiswahili output

- Voice output

- Android deployment


