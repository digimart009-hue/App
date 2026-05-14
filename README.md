# ⚡ NeuroAI — Smart AI Tools Hub

![NeuroAI Banner](https://img.shields.io/badge/NeuroAI-v1.0-blueviolet) ![License](https://img.shields.io/badge/License-MIT-green) ![Status](https://img.shields.io/badge/Status-Active-brightgreen)

A modern, lightning-fast AI tools platform with 15+ powerful utilities, an intelligent chatbot, and a stunning animated interface.

## 🌟 Features

### 🧠 AI-Powered Tools (15+)

1. **📄 Text Summarizer** - Condense long texts into concise summaries
2. **🔢 Word & Character Counter** - Count words and characters instantly
3. **🔐 Password Generator** - Create secure passwords with custom length
4. **🔊 Text to Speech** - Convert text to natural-sounding audio
5. **🎨 Color Palette Generator** - Generate beautiful color schemes
6. **📱 QR Code Generator** - Create QR codes from text or URLs
7. **🌍 Language Translator** - Translate between 7+ languages
8. **🧮 Smart Calculator** - Evaluate mathematical expressions
9. **📏 Unit Converter** - Convert between different length units
10. **🔡 Case Converter** - Change text case (uppercase, lowercase, title)
11. **💱 Currency Converter** - Real-time currency exchange rates
12. **🎲 Random Quote Generator** - Get inspirational quotes
13. **📅 Age Calculator** - Calculate your exact age
14. **🔗 URL Shortener** - Shorten long URLs
15. **📝 BMI Calculator** - Calculate body mass index

### 🤖 AI Chatbot
- Smart rule-based responses
- Context-aware conversations
- Can answer about tools, time, date, and more

### 🎨 User Experience
- **Dark & Light Themes** - Toggle between beautiful themes
- **Animated Interface** - Smooth gradient animations and floating effects
- **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- **Loading Screen** - Stylish loading animation
- **Floating Chatbot** - Always accessible AI assistant

## 📋 Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Design**: Modern gradient UI with Glassmorphism
- **APIs**:
  - QR Code: QRServer API
  - Translation: MyMemory API
  - Currency: ExchangeRate API
  - URL Shortener: TinyURL API
  - Text-to-Speech: Web Speech API
- **Fonts**: Google Fonts (Poppins)

## 🚀 Quick Start

### Installation

1. Clone the repository:
```bash
git clone https://github.com/digimart009-hue/App.git
cd App
```

2. Open in browser:
```bash
# Simply open index.html in your web browser
open index.html
```

### No Build Process Needed!
NeuroAI is a single-file HTML application — just download and run!

## 📚 How to Use

### Text Summarizer
1. Paste long text in the textarea
2. Click "Summarize"
3. Get key sentences extracted

### Password Generator
1. Enter desired length (e.g., 12)
2. Click "Generate"
3. Copy your secure password

### QR Code Generator
1. Enter text or URL
2. Click "Create QR"
3. Scan with any QR reader

### Language Translator
1. Enter text to translate
2. Select target language
3. Click "Translate"
4. Get instant translation

### Currency Converter
1. Enter amount
2. Select source and target currencies
3. Click "Convert"
4. Get live exchange rates

### AI Chatbot
1. Click the 💬 button in bottom-right
2. Type your message
3. Get intelligent responses

## 🎨 Customization

### Change Colors
Edit the CSS variables in the `<style>` section:
```css
/* Primary Colors */
--primary: #00f0ff;  /* Cyan */
--secondary: #a855f7; /* Purple */
--dark-bg: #0a0a23;   /* Dark Blue */
```

### Add More Tools
1. Add a new tool div in the HTML
2. Create a JavaScript function
3. Add event listener to button

Example:
```html
<div class="tool">
  <h3>🆕 New Tool</h3>
  <input id="newInput" placeholder="Input...">
  <button onclick="newTool()">Execute</button>
  <div class="output" id="newOut"></div>
</div>
```

```javascript
function newTool() {
  const input = document.getElementById('newInput').value;
  // Your logic here
  document.getElementById('newOut').innerText = result;
}
```

### Modify Chatbot Responses
Edit the `botReplies` object in the script:
```javascript
const botReplies = {
  "keyword": "Bot response",
  "hello": "Hi there! 👋"
};
```

## 📱 Responsive Breakpoints

- **Desktop**: Full layout (1200px+)
- **Tablet**: Adjusted spacing (768px - 1199px)
- **Mobile**: Single column layout (<768px)

## 🔒 Privacy & Security

- ✅ All processing happens **client-side** (in your browser)
- ✅ No data is stored on servers
- ✅ No cookies or tracking
- ✅ Safe for sensitive information
- ⚠️ Some tools require external APIs for translation, currency, etc.

## 📊 Performance

- **Load Time**: < 2 seconds
- **Bundle Size**: Single 200KB HTML file
- **Browser Support**: All modern browsers (Chrome, Firefox, Safari, Edge)
- **Offline Capability**: Most tools work offline (except API-dependent ones)

## 🐛 Known Limitations

1. **Translator**: Requires internet connection
2. **Currency Converter**: Requires internet for live rates
3. **URL Shortener**: Requires internet
4. **QR Code**: Requires internet to generate image

## 🔧 Troubleshooting

### Tools not working?
- Check browser console (F12) for errors
- Ensure JavaScript is enabled
- Clear browser cache and refresh

### Translation fails?
- Check internet connection
- MyMemory API might be rate-limited (free tier)
- Try again in a few moments

### QR Code won't generate?
- Verify text/URL is entered
- Check internet connection
- QRServer API might be temporarily down

## 📈 Future Enhancements

- [ ] Advanced text analysis with sentiment detection
- [ ] OCR (Optical Character Recognition)
- [ ] Image compression tool
- [ ] Code formatter and beautifier
- [ ] JSON/XML parser
- [ ] Encryption/Decryption tools
- [ ] Dark web integration
- [ ] Voice input for chatbot
- [ ] Multi-language UI support
- [ ] Progressive Web App (PWA) capabilities

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/NewTool`)
3. Make your changes
4. Commit (`git commit -m 'Add new feature'`)
5. Push to branch (`git push origin feature/NewTool`)
6. Open a Pull Request

## 📝 License

MIT License — feel free to use in personal and commercial projects

## 👨‍💻 Author

**NeuroAI Team**  
Built with 💜 in 2026

## 📞 Contact & Support

- 📧 Email: support@neuroai.com
- 🐙 GitHub: [@digimart009-hue](https://github.com/digimart009-hue)
- 🌐 Website: [neuroai.com](https://neuroai.com)

## ⭐ Show Your Support

If you find NeuroAI helpful, please:
- ⭐ Star this repository
- 🐛 Report bugs
- 💡 Suggest features
- 📢 Share with friends

---

**Made with 💜 by NeuroAI — Smart Tools for Smart People**
