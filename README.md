# 🤖 AI Chat & Image Generator

<div align="center">

![AI Chat App Banner](https://img.shields.io/badge/AI-Chat%20%26%20Image%20Generator-blueviolet?style=for-the-badge&logo=openai&logoColor=white)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![MIT License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

A modern, dark-themed AI-powered web application for real-time chat and text-to-image generation — built with vanilla HTML, CSS, and JavaScript.

[Features](#-features) • [Demo](#-demo) • [Installation](#️-installation--setup) • [Usage](#️-how-to-use) • [Tech Stack](#️-tech-stack) • [Contributing](#-contributing)

</div>

---

## 📌 Overview

**AI Chat & Image Generator** is a lightweight, frontend-based web application that lets users chat with an AI assistant and generate images from text prompts — all within a sleek, dark-themed interface. No server required to get started.

---

## ✨ Features

| Feature | Description |
|---|---|
| 💬 **AI Chat System** | Communicate with an AI assistant in real-time |
| 🖼️ **Image Generation** | Generate images from natural language prompts |
| 🔄 **Mode Switching** | Seamlessly toggle between Chat and Image modes |
| 📂 **Chat Sidebar** | Create and manage multiple independent chats |
| 🌙 **Dark UI Design** | Modern, visually appealing dark interface |
| ⚡ **Fast Performance** | Lightweight, static, and fully responsive |
| 🔐 **Session Handling** | Basic logout functionality included |

---

## 🖥️ UI Components

### 🔹 Sidebar
- **+ New Chat** button
- Chat history section
- Settings option

### 🔹 Main Chat Area
- AI response display
- User message bubbles
- Generated image previews

### 🔹 Input Section
- Chat / Image mode toggle
- Prompt input field
- Send button

---

## 🛠️ Tech Stack

**Frontend**
- HTML5
- CSS3 + [Tailwind CSS](https://tailwindcss.com/)
- JavaScript (Vanilla JS)

**Optional Integrations**
- OpenAI API (chat completions + image generation)
- Any compatible AI REST API

---

## 📂 Project Structure

```
AI-Chat-App/
├── index.html          # Main HTML structure
├── style.css           # Custom styles
├── script.js           # App logic & API calls
├── assets/
│   ├── images/         # Static images
│   └── icons/          # UI icons
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/ai-chat-app.git
```

### 2️⃣ Navigate to the Project Folder

```bash
cd ai-chat-app
```

### 3️⃣ Run the Application

Open `index.html` in your browser — no server or build step required!

> 💡 **Tip:** For live reload during development, use the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in VS Code.

---

## ▶️ How to Use

1. Click **+ New Chat** to start a fresh conversation
2. Enter your message or prompt in the input field
3. Select your mode:
   - 💬 **Chat Mode** → for AI conversation
   - 🖼️ **Image Mode** → for image generation
4. Click **Send**
5. View the AI response or generated image inline

---

## 📸 Example

**Prompt:**
```
A tiger walking on a misty road at dawn
```
<img width="1865" height="1064" alt="ai chat 2" src="https://github.com/user-attachments/assets/982dd8c4-9860-4c4a-9e23-46b6e81c02b3" />

<img width="1920" height="1080" alt="ai chat" src="https://github.com/user-attachments/assets/72051816-56d0-4ff8-bf0a-6c0ea619a0d8" />


**Output:**
> 🖼️ AI generates a photorealistic image of a tiger on a road — rendered directly in the chat window.

---

## 🔧 API Configuration (Optional)

To connect a real AI backend:

**1. Obtain an API Key** from your chosen provider (e.g., [OpenAI](https://platform.openai.com/))

**2. Add it to `script.js`:**

```javascript
const API_KEY = "your_api_key_here";
```

**3. Configure the endpoints:**

```javascript
// Chat completions
const CHAT_API_URL = "https://api.openai.com/v1/chat/completions";

// Image generation
const IMAGE_API_URL = "https://api.openai.com/v1/images/generations";
```

> ⚠️ **Security Note:** Never expose API keys in public repositories. Use environment variables or a backend proxy for production deployments.

---

## 🚀 Future Enhancements

- [ ] 🔐 User authentication system
- [ ] ☁️ Backend integration (Node.js / Flask)
- [ ] 💾 Persistent chat history (database)
- [ ] 🎤 Voice input support
- [ ] 📱 Enhanced mobile responsiveness
- [ ] 🌐 Deployment on Netlify / Vercel

---

## 🤝 Contributing

Contributions are welcome! 🎉

```bash
# 1. Fork the repository
# 2. Create a new branch
git checkout -b feature/your-feature-name

# 3. Commit your changes
git commit -m "Add: your feature description"

# 4. Push and open a Pull Request
git push origin feature/your-feature-name
```

Please follow consistent code style and add comments where needed.

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 👩‍💻 Author

**Vaishnavi Sonawane**

---

<div align="center">

Made with ❤️ by Vaishnavi Sonawane

</div>
