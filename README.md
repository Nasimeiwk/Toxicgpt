# Universal AI Chat

A modern, responsive web-based chat interface that connects to multiple AI models through the OpenRouter API.

## Features

- **Multiple AI Models**: Choose from GPT-3.5 Turbo, GPT-4, Claude 3 Haiku, and Gemini Pro
- **Chat History**: Automatically saves all conversations locally
- **System Prompts**: Customize AI behavior with editable system prompts
- **Markdown Support**: Full markdown rendering with syntax highlighting for code blocks
- **Typing Animation**: Optional typewriter effect for AI responses
- **Mobile Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Dark Theme**: Modern dark interface optimized for extended use
- **Export Data**: Download all chats as JSON for backup

## Getting Started

### Prerequisites

You'll need an OpenRouter API key to use this application. Get yours at [openrouter.ai](https://openrouter.ai).

### Installation

This is a static HTML application with no build process required.

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Enter your OpenRouter API key when prompted
4. Start chatting with AI models

### Running Locally

You can serve the application using any static file server. For example:

```bash
# Using Python
python3 -m http.server 8080

# Then open http://localhost:8080 in your browser
```

Or simply open the `index.html` file directly in your browser.

## Usage

1. **Setting Up**: When you first open the app, you'll be prompted to enter your OpenRouter API key
2. **Starting a Chat**: Click the "+" button in the sidebar or start typing in the input box
3. **Changing Models**: Click the "Change" button next to the model name to select a different AI model
4. **Managing Chats**:
   - View chat history in the sidebar
   - Click on any chat to load it
   - Delete individual chats with the X button
   - Clear current chat with the trash icon
5. **Customizing System Prompts**: Click "Edit" in the System Prompt section to customize AI behavior
6. **Settings**: Access settings via the gear icon to:
   - Toggle typing animations
   - Export all chats
   - Clear all data

## Technology Stack

- Pure HTML, CSS, and JavaScript (no frameworks)
- [Tailwind CSS](https://tailwindcss.com) for styling
- [Marked.js](https://marked.js.org) for markdown rendering
- [Highlight.js](https://highlightjs.org) for code syntax highlighting
- [Font Awesome](https://fontawesome.com) for icons
- [OpenRouter API](https://openrouter.ai) for AI model access

## Browser Compatibility

Works on all modern browsers that support:
- ES6+ JavaScript features
- CSS Grid and Flexbox
- LocalStorage API
- Fetch API

## Privacy

All data is stored locally in your browser using LocalStorage. No chat data is sent to any server except the OpenRouter API for generating AI responses. Your API key is stored locally and never transmitted except to authenticate with OpenRouter.

## License

MIT License
