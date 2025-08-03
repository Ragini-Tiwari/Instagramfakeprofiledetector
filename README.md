🕵️‍♀️ Instagram Fake Profile Detector
A tool to detect fake Instagram profiles using the K-Nearest Neighbors (KNN) algorithm, presented with a clean and simple Flask-based web interface.

<!-- Replace this with the actual path to your image -->

📋 Table of Contents
🌟 Features

🎯 Purpose

🚀 Getting Started

📖 Usage

🤝 Contributing

📜 License

🌟 Features
✅ KNN Algorithm: Classifies Instagram profiles as Real or Fake based on extracted features.

🌐 Web Interface: User-friendly UI built with Flask.

📈 Scalability: Capable of processing large sets of profile data efficiently.

🖱️ Drag-and-Drop Upload: Upload profile images effortlessly.

📊 Detailed Insights: Displays classification results with confidence scores.

🎯 Purpose
With the rise of social media usage, fake Instagram profiles are being used to:

Spread misinformation

Conduct scams

Inflate follower counts artificially

This tool is designed to help identify suspicious profiles and promote a safer digital environment.

🚀 Getting Started
Follow the steps below to run the project locally:

1. Clone the Repository
git clone https://github.com/Ragini-Tiwari/instagram-fake-profile-detector.git
cd instagram-fake-profile-detector

2. Create and Activate a Virtual Environment
python -m venv venv
For Windows:
venv\Scripts\activate
For macOS/Linux:
source venv/bin/activate

3. Install Dependencies
pip install -r requirements.txt

4. Train the KNN Model
python train_model.py

5. Launch the Flask Application
python app.py

6. Open the App
Visit: http://127.0.0.1:5000/

📖 Usage
Upload Profile Image
Drag and drop or use the file selector to upload an Instagram profile image.

Analysis
The tool extracts features from the image and applies the KNN algorithm to determine if the profile is fake or real.

View Results
✔️ Classification: Real / Fake
📉 Confidence Score
🔍 Suggested Actions (for suspicious profiles)

🤝 Contributing
Contributions are welcome! 🚀

Steps to contribute:

Fork the repo

Create a new branch

Make your changes

Submit a pull request

For major changes, please open an issue first to discuss.

✅ Don’t forget to update/add tests if needed.

📜 License
This project is licensed under the MIT License.
See the LICENSE file for details.

Made with 💻 by Ragini Tiwari



