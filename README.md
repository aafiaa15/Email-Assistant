

Video LINK:https://github.com/user-attachments/assets/9f10ff61-7e4f-4f2e-9533-f603e106ac62

# 📧 Smart Email Assistant

An AI-powered email assistant that generates context-aware replies using Google's Gemini API. Built with a robust Spring Boot backend, a responsive React frontend, and a browser extension for seamless real-time assistance in email platforms.

## 🚀 Features

- ✨ Context-aware reply generation using Gemini API
- 🔐 Secure JWT-based user authentication
- ⚙️ RESTful API architecture with Spring Boot
- 🎨 Modern and responsive UI built with React & Tailwind CSS
- 🧩 Browser extension integration for real-time email enhancement
- 📊 Optimized performance for fast and efficient response generation

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Tailwind CSS
- Recoil

**Backend:**
- Spring Boot
- Google Gemini API
- JWT Authentication
- Maven

**Others:**
- Browser Extension (Manifest v3)
- Docker (optional)
- Cloudflare (optional for deployment)

## 🧠 How It Works

1. **User** opens their email client with the browser extension active.
2. The extension captures the context of the email.
3. The request is sent securely to the Spring Boot backend via a REST API.
4. Gemini API generates a smart reply.
5. The reply is returned and displayed in the extension for quick insertion.

## 🔒 Authentication

- JWT (JSON Web Tokens) are used to handle secure user sessions.
- Access tokens are verified on each request to ensure data protection.

## 📁 Project Structure

```bash
📦 smart-email-assistant
├── backend
│   └── src/main/java/com/aafia/emailassistant
├── frontend
│   └── src/components, pages, utils
├── extension
│   └── manifest.json, background.js, content.js
