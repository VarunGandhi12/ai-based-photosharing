Smart Wedding Photo Sharing Platform

A photo-sharing platform designed to make wedding albums smarter. Using facial recognition and AI-based sorting, the system automatically organizes group photos and delivers them to the right people via WhatsApp. Guests don’t need to scroll through hundreds of images — they receive only the photos they appear in.

✨ Features

 Facial Recognition Sorting – Detects individuals in group wedding photos.

 Automated WhatsApp Delivery – Sends images directly to identified guests.

 User Profiles & Authentication – Each guest has a secure profile for photo management.

 Asynchronous Media Handling – Smooth processing for large photo batches.

 Photo Archiving – Organizes albums with MongoDB backend.

 Tech Stack

Backend: Python, Flask

AI/ML: Hugging Face Face Detection Model, OpenCV

Database: MongoDB

Frontend: HTML, CSS, JavaScript

Messaging Integration: WhatsApp API (via Twilio / custom integration)

⚙️ Installation & Setup

Clone the repo:

git clone https://github.com/<your-username>/ai-based-photosharing.git
cd ai-photo-share


Install dependencies:

pip install -r requirements.txt


Configure MongoDB connection and WhatsApp API keys in .env.

Run the app:

python app.py

🎤 How It Works

Admin uploads wedding photos in bulk.

The system detects faces and matches them with guest profiles.

Identified guests receive their photos directly on WhatsApp.

Guests can log in to view/download archived photos.
