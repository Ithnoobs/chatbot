# AI Chatbot

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Status](https://img.shields.io/badge/Status-In%20Development-orange)
![Academic Project](https://img.shields.io/badge/Type-Academic%20Project-blue)

## Live Demo

**[Try the Chatbot Here](https://ithnoobs.github.io/chatbot/)**

## Overview

A modern, responsive AI-powered chatbot web application built with vanilla HTML, CSS, and JavaScript. This chatbot integrates with Google's Gemini API to provide intelligent conversational responses.

## Features

- Real-time AI-powered conversations using Google Gemini 2.5 Flash
- Modern and responsive UI design
- Emoji picker integration
- Image attachment support
- Smooth animations and thinking indicators
- Mobile-friendly popup interface

## Design

View the UI/UX mockup on Figma:

**[Figma Design Mockup](https://www.figma.com/design/vahxPXUoWDZFdj3iTrDEU6/AI-Chatbot?m=auto&t=XwNP6w2vKhlGxrNb-1)**

## Project Structure

```text
chatbot/
├── index.html          # Main HTML structure
├── style.css           # Styling and animations
├── script.js           # Core JavaScript logic and API integration
├── docs/
│   ├── figmaMockUp.txt # Figma design link reference
│   ├── Chatbotai2.pdf  # Project documentation
│   └── spm.pdf         # Software project management documentation
└── README.md           # Project documentation
```

## Technologies Used

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure and markup |
| CSS3 | Styling and animations |
| JavaScript (ES6+) | Core functionality and API calls |
| Google Gemini API | AI conversation engine |
| Emoji Mart | Emoji picker library |
| Material Symbols | Icon library |

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari)
- Google Gemini API key

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ithnoobs/chatbot.git
   ```

2. Navigate to the project directory:

   ```bash
   cd chatbot
   ```

3. Open `index.html` directly in your browser - no server required!

### Configuration

Replace the API key in `script.js` with your own Google Gemini API key:

```javascript
const API_KEY = "YOUR_API_KEY_HERE";
```

> **Note:** Never commit API keys to version control. Consider using environment variables for production.

## Usage

1. Click the chat button in the bottom-right corner to open the chatbot
2. Type your message in the input field
3. Optionally attach an image using the attachment button
4. Use the emoji picker to add emojis
5. Press Enter or click the send button to send your message
6. Wait for the AI response

## Documentation

Additional project documentation can be found in the `docs/` folder:

- Project specifications and requirements
- Software project management documentation

## Contributing

This is an academic project. Contributions, issues, and feature requests are welcome for educational purposes.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```text
MIT License

Copyright (c) 2024

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Acknowledgments

- [Google Gemini API](https://ai.google.dev/) for AI capabilities
- [Emoji Mart](https://github.com/missive/emoji-mart) for the emoji picker
- [Material Symbols](https://fonts.google.com/icons) for icons

## Author

Academic Project

---

*This project was created for educational purposes.*
