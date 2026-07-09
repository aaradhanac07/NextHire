# 🚀 NextHire

**NextHire** is a comprehensive, modern platform designed to help candidates prepare for their next big career opportunity. From automated resume analysis to mock interviews and online assessments, NextHire provides all the tools you need to ace your next hiring process.

![NextHire Hero](https://via.placeholder.com/1200x400.png?text=NextHire+-+Elevate+Your+Career)

## ✨ Features

- **📄 Resume Analyzer**: Upload your resume (PDF) and get instant feedback and parsing using AI-driven analysis.
- **💻 Online Assessments (OA)**: Take realistic coding and aptitude tests with an intuitive UI.
- **🧠 CS Fundamentals**: Brush up on core computer science concepts with dedicated topics and study materials.
- **🗣️ Mock Interviews**: Practice your interview skills with structured mock interview sessions.
- **📊 Detailed Reports**: Get in-depth performance reports for your online assessments and mock interviews.
- **🕒 Interview History**: Keep track of your past interviews and track your progress over time.
- **🔐 Secure Authentication**: Fast and secure login using Firebase Auth.

## 🛠️ Tech Stack

NextHire is built with a modern, scalable **MERN** stack:

### Frontend
- **React 19** with **Vite** for lightning-fast development and optimized builds.
- **Redux Toolkit** for predictable state management.
- **Tailwind CSS v4** for beautiful, responsive, and customizable styling.
- **Framer Motion** for smooth, micro-interactions and animations.
- **Recharts** & **react-circular-progressbar** for data visualization.
- **Firebase** for Authentication.

### Backend
- **Node.js** & **Express** for a robust and scalable REST API.
- **MongoDB** & **Mongoose** for flexible data storage.
- **JWT (JSON Web Tokens)** & **Bcrypt** for secure authorization and password hashing.
- **Multer** for handling file uploads (resumes).
- **pdfjs-dist** for parsing PDF resumes on the server.

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- MongoDB (local or Atlas)
- Firebase Project (for client-side auth)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/NextHire.git
   cd NextHire
   ```

2. **Setup Environment Variables**
   - In the `client` directory, create a `.env` file and add your Firebase credentials.
   - In the `server` directory, create a `.env` file and add your MongoDB URI, JWT secret, etc.

3. **Install Dependencies & Start**
   You can use the provided setup scripts to easily install and run both client and server:
   
   **Windows:**
   ```powershell
   ./setup.ps1
   ```
   **Mac/Linux:**
   ```bash
   ./setup.sh
   ```
   
   *Alternatively, you can run them manually:*
   ```bash
   # Terminal 1 - Server
   cd server
   npm install
   npm run dev

   # Terminal 2 - Client
   cd client
   npm install
   npm run dev
   ```

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📝 License
This project is licensed under the ISC License.
