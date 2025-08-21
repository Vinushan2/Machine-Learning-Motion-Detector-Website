🚀 Machine Learning Motion Detector Website

A modern web application built with React + Tailwind CSS featuring:

🌐 A sleek Landing Page showcasing the project.

📊 A Motion Detector Dashboard powered by JavaScript + Machine Learning techniques (frame-by-frame motion detection).

🎨 Modern UI/UX with animations (Framer Motion, shadcn/ui).

📹 Real-time webcam integration for live motion detection.

📸 Features

⚡ Landing Page

Hero section with animations

Smooth navigation

About & Features sections

🖥 Dashboard

Webcam live feed

Real-time motion detection overlay

Sensitivity control (slider)

Event log (tracks detected motion events)

Motion activity chart (Recharts)

🎨 Modern Design

Tailwind CSS + shadcn/ui

Framer Motion animations

Responsive across devices

🛠 Tech Stack

Frontend: React, Tailwind CSS, shadcn/ui

Motion Detection: JavaScript (Webcam + Canvas frame comparison)

Animations: Framer Motion

Charts: Recharts

Icons: Lucide React

📂 Project Structure
├── src
│   ├── components
│   │   ├── LandingPage.jsx
│   │   ├── Dashboard.jsx
│   │   ├── MotionDetector.jsx
│   │   └── Navbar.jsx
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── public
│   └── favicon.ico
├── package.json
└── README.md

🚀 Getting Started
1️⃣ Clone the Repository
git clone https://github.com/your-username/motion-detector-website.git
cd motion-detector-website

2️⃣ Install Dependencies
npm install

3️⃣ Run Development Server
npm run dev

4️⃣ Build for Production
npm run build

🎥 How Motion Detection Works

Accesses webcam feed using MediaDevices API.

Captures frames and draws them on an invisible canvas.

Compares pixel differences between consecutive frames.

If pixel change exceeds sensitivity threshold, motion is detected.

Detected motion triggers UI overlays and event logging.

📊 Example Dashboard Preview

Live Webcam stream with motion highlight

Activity chart for tracking detections

Event logs with timestamps

📜 License

This project is licensed under the MIT License.
