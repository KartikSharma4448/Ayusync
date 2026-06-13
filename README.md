# AayuSync

![License](https://img.shields.io/badge/license-MIT-green)
![Node](https://img.shields.io/badge/node-20.x-blue)
![TypeScript](https://img.shields.io/badge/typescript-5.6-blue)
![Django](https://img.shields.io/badge/stack-express%2Breact%2Bvite-orange)

AayuSync is a smart healthcare platform designed to unify patient access, emergency response, and medical record visibility through ABHA-powered authentication and a modern dashboard experience.

## ✨ Features

- ABHA-based login flow with OTP verification
- Patient dashboard with medical records and health insights
- Emergency SOS dispatch with nearby ambulance tracking
- QR-based profile sharing for doctors and caregivers
- Responsive UI built with React, Tailwind CSS, and shadcn-inspired components

## 🛠 Tech Stack

- Frontend: React, TypeScript, Vite, Tailwind CSS
- Backend: Express.js, TypeScript
- Data: In-memory storage layer with schema-based structures
- Auth: ABHA-style OTP demo flow

## 🚀 Getting Started

### Prerequisites

- Node.js 20+
- npm 10+

### Installation

```bash
npm install
```

### Run locally

```bash
npm run dev
```

The app will start on port 5000 by default.

## 📁 Project Structure

```text
client/        # React frontend
server/        # Express API routes and app setup
shared/        # Shared schemas and types
script/        # Build utilities
```

## 🔐 Demo Access

Use any of the sample ABHA IDs for testing:

- ABHA001
- ABHA002
- ABHA003
- ABHA004
- ABHA005

After requesting OTP, use the demo OTP shown on screen to continue.

## 📜 License

This project is licensed under the MIT License.

## 🤝 Contributing

Contributions are welcome. Please open an issue or submit a pull request for improvements.
