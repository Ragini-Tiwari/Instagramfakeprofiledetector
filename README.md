Instagram Fake Profile Detector

---

A tool to detect fake profiles on Instagram using the K-Nearest Neighbors (KNN) algorithm, hosted as a Flask web application.

📋 Table of Contents
🌟 Features
🎯 Purpose
🚀 Installation and Setup
📖 Usage
📂 Project Structure
🤝 Contributing
📜 License
🙏 Acknowledgments

---

🌟 Features
KNN Algorithm: Classifies profiles as real or fake using profile features.
Web Interface: A simple, user-friendly web interface for analysis.
Scalability: Handles large volumes of profile data efficiently.
Drag-and-Drop Upload: Allows users to easily upload profile images.
Detailed Insights: Provides classification confidence scores.

---

🎯 Purpose
With the growing impact of social media, fake profiles have become a significant problem, leading to:

1. Spreading misinformation.
2. Engaging in scams.
3. Artificially inflating follower counts.
4. This tool aims to identify suspicious profiles and promote a safer online environment.

🚀 Installation and Setup
1. Prerequisites
Python 3.8 or higher installed on your machine.
Basic knowledge of running Python and Flask applications.
2. Steps to Set Up
bash
Copy code
# Clone the repository
git clone https://github.com/Ragini-Tiwari/instagram-fake-profile-detector.git
cd instagram-fake-profile-detector

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # For Windows, use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Train the KNN model (example command, adjust based on implementation)
python train_model.py

# Run the Flask application
python app.py
3. Access the Application
Once the application is running, open your browser and go to:
http://127.0.0.1:5000/

📖 Usage
1. Upload Profile Image
Drag and drop an image or use the "Choose File" button to upload an Instagram profile image.
2. Analysis
The tool extracts features and uses the KNN algorithm to classify the profile as Real or Fake.
3. Results
View detailed results with:
Profile Classification: Real/Fake.
Confidence Score: Probability of classification.
Suggested next steps for suspicious profiles.
