# 🤖 AI Chatbot POC


==================================================================================================================
THE API KEY USAGE IS LIMITED. DONT USE MORE THAN 5 TIMES THIS IS POC ONLY
==================================================================================================================
A modern, responsive AI chatbot proof-of-concept built with HTML, CSS, and JavaScript, featuring a sleek dark theme and smooth animations.

## ✨ Features

### 🎨 Modern UI/UX
- **Dark Theme**: Trending dark gradient background with glassmorphism effects
- **Responsive Design**: Optimized for desktop and mobile devices
- **Smooth Animations**: Fade-in messages, typing indicators, and hover effects
- **Modern Typography**: Uses Inter font for clean, professional appearance

### 🚀 Functionality
- **Real-time Chat**: Interactive conversation with AI using Groq API
- **Enter Key Support**: Send messages by pressing Enter or clicking Send button
- **Typing Indicators**: Shows "🤔 Thinking..." during AI processing delay
- **Error Handling**: Graceful error messages for API failures
- **Auto-scroll**: Chat container automatically scrolls to show latest messages

### 🎯 Technical Features
- **Artificial Delay**: 1.5-second thinking delay for natural conversation flow
- **API Integration**: Powered by Groq's Llama 3.1 model
- **Modular Code**: Clean, maintainable JavaScript structure
- **Cross-browser Compatible**: Works on all modern browsers

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **API**: Groq API (Llama 3.1-8B Instant model)
- **Fonts**: Google Fonts (Inter)
- **Styling**: Modern CSS with gradients, backdrop-filter, and animations

## 📋 Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection for API calls
- Valid Groq API key

## 🚀 Installation & Setup

1. **Clone or Download** the project files
2. **Open `index.html`** in your web browser
3. **Start chatting!** The chatbot is ready to use

## 🔧 Configuration
## 📖 Usage

### Basic Chat
1. Type your message in the input field
2. Press **Enter** or click the **Send** button
3. Wait for the AI to respond (shows "🤔 Thinking..." indicator)
4. Read the AI's response in the chat area

### Features Overview
- **Message History**: All conversation history is displayed in the chat
- **Auto-scroll**: New messages automatically scroll into view
- **Responsive**: Works on phones, tablets, and desktops
- **Keyboard Friendly**: Full keyboard navigation support

## 🎨 Customization

### Theme Colors
Modify the CSS variables in `index.html` to customize colors:

```css
/* Background gradient */
background: linear-gradient(135deg, #0f0f0f 0%, #1a1a1a 50%, #2a2a2a 100%);

/* Accent color */
#667eea

/* Message bubbles */
.message.user background: linear-gradient(135deg, #667eea, #764ba2);
.message.ai background: rgba(255,255,255,0.95);
```

### Animation Timing
Adjust animation durations in the CSS:

```css
/* Message fade-in */
animation: fadeIn 0.4s ease;

/* Thinking delay (in JavaScript) */
setTimeout(() => { /* show typing dots */ }, 1500);
```

## 📱 Responsive Design

The chatbot is fully responsive and works on:
- **Desktop**: Full feature set with optimal layout
- **Tablet**: Adapted touch interface
- **Mobile**: Optimized for small screens with proper touch targets

## 🔍 API Details

### Groq Integration
- **Model**: `llama-3.1-8b-instant`
- **Endpoint**: `https://api.groq.com/openai/v1/chat/completions`
- **Temperature**: 0.7 (balanced creativity and coherence)
- **System Prompt**: "You are a helpful assistant."

### Rate Limits
- Respects Groq's API rate limits
- Includes error handling for API failures
- Graceful degradation on network issues

## 🐛 Troubleshooting

### Common Issues

**API Errors:**
- Check your internet connection
- Verify your Groq API key is valid and has credits
- Ensure the API key is correctly set in the code

**Display Issues:**
- Use a modern browser (Chrome 90+, Firefox 88+, Safari 14+)
- Clear browser cache if styles don't load
- Check console for JavaScript errors

**Performance Issues:**
- Close other browser tabs to free up memory
- Ensure stable internet connection for API calls

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Make your changes and test thoroughly
4. Commit your changes: `git commit -am 'Add new feature'`
5. Push to the branch: `git push origin feature-name`
6. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Groq** for providing fast and reliable AI API
- **Google Fonts** for the Inter typeface
- **Open source community** for inspiration and best practices

---

**Made with for modern web development**

*Last updated: 03-01-2026*

