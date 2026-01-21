🌸 Pico — Empowering Women's Health with Technology

Pico is an AI-powered healthcare platform designed to empower women, especially in rural areas, by helping them detect and manage PCOD/PCOS using smart technology. By bridging the gap caused by limited access to doctors and lack of awareness, Pico leverages AI, ML, and modern web technologies to improve women's health outcomes.

🔹 Why Pico?

Millions of women face challenges due to limited awareness and access to healthcare. Pico addresses this by:

Detecting PCOD/PCOS early with AI-powered analysis

Connecting users with verified healthcare professionals

Providing privacy-first community spaces for sharing and support

Offering habit tracking and reminders to encourage healthier lifestyles

Pico combines AI, Machine Learning, Web3 security, and modern web technologies into a single, easy-to-use platform.

✨ Key Features
1. AI-Powered Health Assessment

Quickly evaluate your PCOD/PCOS risk using a short questionnaire

Machine Learning model trained for 99% accuracy

Receive actionable insights instantly

2. Doctor Consultation Booking

Schedule appointments with verified doctors nearby

Manage consultations directly on the platform

3. Interactive AI Chatbot

Ask questions about PCOD/PCOS and women’s health

Responses powered by Gemini API, ensuring clarity and accuracy

4. Personal Health & Fitness Tracker

Track cycles, workouts, and habits

Daily SMS reminders via Twilio API for accountability

5. Secure Community Hub

Share stories and experiences in a women-only space

Face Recognition ensures privacy and safety

6. Story Sharing Dashboard

Publish stories publicly or privately

Control visibility with privacy settings

7. Web3 Security

Login with MetaMask for enhanced security and full data privacy

| Layer             | Technology                       |
| ----------------- | -------------------------------- |
| Frontend          | React, Vite, Tailwind CSS        |
| Backend           | Node.js, Express.js              |
| Database          | MongoDB                          |
| Authentication    | MetaMask (Web3)                  |
| Machine Learning  | Python, Scikit-learn, TensorFlow |
| AI Chatbot        | Gemini API                       |
| SMS Notifications | Twilio API                       |
| Face Recognition  | Custom ML + DL Model             |

🚀 Getting Started
1. Clone the Project
git clone https://github.com/yashch3101/PCOD_HealthCare
cd Pico_Website

2. Install Dependencies
npm install
cd frontend && npm install
cd ../backend && npm install

3. Configure Environment Variables

Create a .env file:

MONGO_URI=your_mongodb_connection_string
GEMINI_API_KEY=your_gemini_api_key
TWILIO_ACCOUNT_SID=your_twilio_sid
TWILIO_AUTH_TOKEN=your_twilio_token
META_MASK_KEY=your_metamask_key

4. Run the Application
# Start Frontend
npm run dev

# Start Backend
nodemon server.js

# Run ML Model (optional)
cd frontend/pcod
python app.py

🧠 Machine Learning Model

Combines Random Forest and Logistic Regression for PCOD/PCOS detection

Achieves ~99% prediction accuracy

Accessible via REST API for real-time results
