# Anonymous Chat Application 🔥

A modern, AI-powered anonymous chat application that connects users with virtual chat partners for engaging conversations. Built with vanilla JavaScript and powered by Google's Gemini AI.

## ✨ Features

- **Anonymous Chatting**: Connect with AI-powered chat partners without registration
- **Realistic Conversations**: AI partners with unique personalities, ages, and interests
- **Hinglish Support**: Natural Hindi-English mix for authentic Indian conversations
- **Gender Selection**: Choose your preferred chat partner gender
- **Real-time Typing Indicators**: See when your partner is typing
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Modern UI**: Beautiful gradient design with smooth animations
- **Quick Partner Switching**: Easily connect with a new partner anytime

## 🚀 Technologies Used

- **HTML5** - Structure and semantics
- **CSS3** - Styling with gradients, animations, and flexbox
- **Vanilla JavaScript** - Core functionality and API integration
- **Google Gemini API** - AI-powered conversational responses
- **Gemini 2.0 Flash Model** - Fast, natural language processing

## 🎯 Key Functionalities

### AI-Powered Chat Partners
- Dynamically generated profiles with age (18-29), personality traits, and interests
- Context-aware conversations that remember previous messages
- Natural Hinglish responses mimicking real Indian chat patterns
- Emotional and engaging responses with varied personalities

### User Interface
- **Gender Selection Screen**: Choose between male/female options
- **Connecting Animation**: Visual feedback while finding a partner
- **Chat Interface**: Clean, modern messaging layout
- **Message Timestamps**: Track conversation flow
- **Action Buttons**: Easy partner switching and disconnection

### Smart Features
- Input validation (max 500 characters)
- Enter key support for sending messages
- Auto-scroll to latest messages
- Warning before leaving active chats
- Responsive typing delays based on message length

## 📋 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/anonymous-chat.git
   cd anonymous-chat
   ```

2. **Get Gemini API Key**
   - Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Generate your free API key

3. **Configure API Key**
   - Open `index.html`
   - Replace `'you gemini api key'` with your actual API key:
   ```javascript
   const API_KEY = 'YOUR_ACTUAL_API_KEY_HERE';
   ```

4. **Launch the Application**
   - Simply open `index.html` in a modern web browser
   - No server or build process required!

## 🎨 Customization Options

### Modify Personalities
Edit the `generatePersonality()` function to add new personality types:
```javascript
const personalities = [
  'friendly and outgoing',
  'your custom personality',
  // Add more...
];
```

### Adjust Interests
Customize the `generateInterests()` function:
```javascript
const interests = [
  ['music', 'movies', 'dancing'],
  ['your', 'custom', 'interests'],
  // Add more...
];
```

### Change Response Length
Modify `maxOutputTokens` in the API calls:
```javascript
maxOutputTokens: 60 // Adjust for longer/shorter responses
```

## 🔒 Privacy & Safety

- No user data is stored or tracked
- Conversations are ephemeral (not saved)
- Anonymous by design - no registration required
- AI partners are clearly virtual entities

## 📱 Browser Compatibility

- ✅ Chrome/Edge (Recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## ⚙️ Configuration Parameters

```javascript
// API Configuration
const API_KEY = 'your-api-key';
const MODEL = 'gemini-2.0-flash';

// Chat Settings
maxlength="500" // Maximum message length
temperature: 0.9 // Response creativity (0-1)
topP: 0.95 // Response diversity
```

## 🐛 Troubleshooting

**API Errors**
- Verify your API key is correct and active
- Check your internet connection
- Ensure you haven't exceeded API quota

**UI Issues**
- Clear browser cache
- Try a different browser
- Check console for JavaScript errors

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## ⚠️ Disclaimer

This is an AI-powered chat application for entertainment purposes. The chat partners are AI-generated and not real people. Users should be aware they are conversing with an AI model.

## 🔮 Future Enhancements

- [ ] Multiple language support
- [ ] Chat history export
- [ ] Custom themes
- [ ] Voice message support
- [ ] Group chat functionality
- [ ] User feedback system

## 👨‍💻 Developer

Created with ❤️ by nikhilkumarmaurya 

---
👉 code written by Ai under full my algorithm.

**Star ⭐ this repository if you found it helpful!**
