# OpenSAC - Open Source AI Chatbot

<div align="center">

![OpenSAC Logo](https://img.shields.io/badge/OpenSAC-Open%20Source%20AI%20Chatbot-10a37f?style=for-the-badge&logo=openai&logoColor=white)

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![Groq](https://img.shields.io/badge/Powered%20by-Groq-10a37f)](https://groq.com)

**A modern, free chat interface for Groq Cloud AI models**

[Features](#features) •
[Installation](#installation) •
[Usage](#usage) •
[Configuration](#configuration) •
[Contributing](#contributing) •
[License](#license)

</div>

---

## 📖 About

OpenSAC (Open Source AI Chatbot) is a single-page web application that provides an elegant and intuitive user interface for interacting with **Groq Cloud** language models.

Bring your own API key (BYOK) and start chatting immediately! Your key stays safely stored in your browser's localStorage, ensuring maximum privacy.

### ✨ Features

- 🎨 **Modern Interface**: Clean, responsive dark-mode design
- 🔑 **BYOK**: Use your own Groq API key (free tier available)
- 💬 **Multiple Chats**: Create and manage unlimited conversations
- 🌐 **Web Search**: Real-time web search during chat
- 🧠 **Thinking/Reasoning**: Advanced reasoning mode for compatible models
- 📎 **File/Image Upload**: Attach files to your conversations
- 🌍 **Multilingual**: Italian and English support
- 📱 **Responsive**: Works perfectly on desktop, tablet, and mobile
- 🎯 **Markdown & Code**: Full formatting support with syntax highlighting
- 💾 **LocalStorage**: All data stored only in your browser
- 🚫 **Rate Limiting**: Automatic daily limit handling
- ⚡ **Fast**: Single page, no backend required

### 🎮 Supported Models

| Model | Size | Web Search | Thinking | Speed |
|-------|------|------------|----------|-------|
| GPT-OSS 120B | 120B | ✅ | ✅ | Medium |
| GPT-OSS 20B | 20B | ✅ | ✅ | High |
| Llama 3.3 70B Versatile | 70B | ✅ | ✅ | Medium |
| Llama 3.1 8B Instant | 8B | ✅ | ❌ | Very High |

## 🚀 Installation

### Prerequisites

- A free API key from [Groq Cloud](https://console.groq.com)
- A modern web browser (Chrome, Firefox, Safari, Edge)

### Method 1: Direct Use (Recommended)

1. Clone the repository:
```bash
git clone https://github.com/yourusername/opensac.git
cd opensac
```

2.Open index.html in your browser:
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html

3. Enter your Groq API key when prompted

### Method 2: Local Server
# Using Python 3
python -m http.server 8000

# Using Node.js (npx)
npx serve

# Using PHP
php -S localhost:8000

Then visit http://localhost:8000

### Method 3: GitHub Pages

1. Fork the repository

2. Go to Settings > Pages

3. Select the main branch

4. your OpenSAC will be available at https://yourusername.github.io/opensac

### 💡 Usage

## First Launch

1. Open OpenSAC in your browser

2. Click on API Settings (key icon)

3. Enter your Groq API key (starts with gsk_...)

4. Select your desired model

5. Click Save & Start

## Chatting

- New Chat: + button in the sidebar

- Web Search: Toggle 🌐 before sending

- Thinking: Toggle 🧠 for more reasoned responses

- Files: Click 📎 to attach images or documents

- Delete Chat: Trash icon on chat in sidebar

- Switch Language: 🌍 button at bottom of sidebar

## Keyboard Shortcuts

- Enter: Send message

- Shift + Enter: New line

- Click outside sidebar (mobile): Close menu

### 🔧 Configuration

1. Getting a Groq API Key

2. Go to console.groq.com

3. Sign up for free with Google, GitHub, or email

4. In the dashboard, go to API Keys

5. Click Create API Key

6. Copy the key (format: gsk_...)

7. Paste it into OpenSAC

## Limits

- Groq Free Tier: Variable limits depending on the model

- Rate Limiting: OpenSAC automatically handles 24h blocks

- Local Storage: Conversations take up localStorage space

### 🛠️ Tech Stack

- Frontend: HTML5, CSS3, Vanilla JavaScript

- API: Groq Cloud API (OpenAI-compatible)

Libraries:
 * Marked.js - Markdown parsing

 * Highlight.js - Syntax highlighting

 * Font Awesome - Icons

### 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository

2. Create a feature branch (git checkout -b feature/AmazingFeature)

3. Commit your changes (git commit -m 'Add some AmazingFeature')

4. Push to the branch (git push origin feature/AmazingFeature)

5. Open a Pull Request

## Guidelines

- Keep code clean and commented

- Test changes across different browsers

- Update documentation if needed

- Follow existing commit conventions

### 📄 License

This project is licensed under the GNU Affero General Public License v3.0 (AGPL-3.0).

See the LICENSE file for full details.
What AGPL-3.0 Means

    ✅ Commercial Use: You can use OpenSAC for commercial purposes

    ✅ Modification: You can modify the code freely

    ✅ Distribution: You can distribute copies of the software

    ✅ Private Use: You can use it privately without restrictions

    ⚠️ Copyleft: If you distribute modified versions, you must keep the same license

    ⚠️ Network Use: If you use OpenSAC as a web service, you must make the source code available

🙏 Credits

    Groq for the fast and free API

    Marked.js and Highlight.js for content rendering

    Font Awesome for icons

    The open source community for inspiration and support

📞 Support

    🐛 Bugs: Open an issue

    💡 Feature Requests: Use discussions

    ❓ Questions: Check the FAQ first or start a discussion

⚠️ Disclaimer

OpenSAC is not affiliated with Groq, Inc. It is an independent open source project that uses Groq Cloud's public API. Users are responsible for their own API usage and must comply with Groq's terms of service.
<div align="center">

Made with ❤️ by cribest7890

⬆ Back to top
</div> ```
