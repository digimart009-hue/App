# 🧠 NeuroAI Features Documentation

## Complete Feature List

### 1. 📄 Text Summarizer
**What it does**: Extracts key sentences from long text to create a concise summary.

**How to use**:
1. Paste or type your long text
2. Click "Summarize"
3. Get a 2-sentence summary

**Best for**: Articles, essays, research papers

**Processing**: Client-side (no internet required)

---

### 2. 🔢 Word & Character Counter
**What it does**: Counts words and characters in real-time.

**Features**:
- Word count
- Character count (including spaces)
- Handles multiple spaces

**Use cases**: Content creators, writers, SEO optimization

---

### 3. 🔐 Password Generator
**What it does**: Creates secure, random passwords with mixed characters.

**Character set**: 
- Uppercase: A-Z
- Lowercase: a-z
- Numbers: 0-9
- Symbols: !@#$%^&*

**Customization**: Set length (default: 12)

**Security note**: Generated locally, not stored anywhere

---

### 4. 🔊 Text to Speech
**What it does**: Converts written text to spoken audio using browser's native speech synthesis.

**Features**:
- Natural voice output
- Works in multiple languages
- Adjustable speed (browser-dependent)

**Browser support**: Chrome, Firefox, Safari, Edge

**Note**: Quality depends on system voice

---

### 5. 🎨 Color Palette Generator
**What it does**: Generates 5 random hex colors with visual preview.

**Output**: 
- Color hex code
- Visual color box
- Box shadow matching color

**Use for**: Design inspiration, color schemes, UI development

**Refresh**: Click button again to generate new palette

---

### 6. 📱 QR Code Generator
**What it does**: Creates QR codes from text or URLs.

**Input**: Any text, URL, or data

**Output**: 150x150px QR image

**API**: Uses QRServer API

**Use cases**:
- WiFi sharing (encode credentials)
- Link sharing
- Contact info
- Business cards

**Internet required**: Yes

---

### 7. 🌍 Language Translator
**What it does**: Translates text between multiple languages.

**Supported languages**:
- English (en)
- Urdu (ur)
- Hindi (hi)
- Arabic (ar)
- French (fr)
- Spanish (es)
- Chinese (zh)

**API**: MyMemory Translation API

**Internet required**: Yes

**Rate limit**: Free tier limited

---

### 8. 🧮 Smart Calculator
**What it does**: Evaluates mathematical expressions safely.

**Supported operations**:
- Addition: +
- Subtraction: -
- Multiplication: *
- Division: /
- Parentheses: ()
- Complex expressions: (5+3)*2

**Safety**: Regex sanitization prevents injection

**Example**: `(10 * 5) - (3 + 2)` = 45

---

### 9. 📏 Unit Converter (Length)
**What it does**: Converts between length measurements.

**Units**:
- Meters (m)
- Kilometers (km)
- Centimeters (cm)
- Feet (ft)
- Inches (in)

**Precision**: 4 decimal places

**Use for**: Engineering, construction, international communication

---

### 10. 🔡 Case Converter
**What it does**: Converts text between different cases.

**Modes**:
1. **UPPERCASE**: All letters capitalized
2. **lowercase**: All letters lowercase
3. **Title Case**: First letter of each word capitalized

**Use for**: Text formatting, code generation, content creation

---

### 11. 💱 Currency Converter
**What it does**: Converts between currencies using live exchange rates.

**Supported currencies**:
- USD (US Dollar)
- EUR (Euro)
- GBP (British Pound)
- PKR (Pakistani Rupee)
- INR (Indian Rupee)

**API**: ExchangeRate API

**Features**:
- Real-time rates
- 2 decimal precision
- Quick conversion

**Internet required**: Yes

---

### 12. 🎲 Random Quote Generator
**What it does**: Displays inspirational quotes randomly.

**Quote database**: 6 built-in quotes

**Featured quotes**:
- Peter Drucker: "The best way to predict the future is to create it."
- Winston Churchill: "Success is not final; failure is not fatal."
- Norman Vaughan: "Dream big and dare to fail."
- Sam Levenson: "Don't watch the clock; do what it does."
- Eleanor Roosevelt: "The future belongs to those who believe."
- Steve Jobs: "Innovation distinguishes a leader from a follower."

**Customization**: Easy to add more quotes

---

### 13. 📅 Age Calculator
**What it does**: Calculates exact age from date of birth.

**Input**: Date picker

**Output**: Age in years

**Accuracy**: Accounts for:
- Current date/time
- Month and day compared to DOB
- Leap years automatically

**Use for**: Demographics, age verification, birthday reminders

---

### 14. 🔗 URL Shortener
**What it does**: Compresses long URLs into short, shareable links.

**API**: TinyURL API

**Features**:
- Instant shortening
- Clickable output link
- Works with any URL

**Use for**: Social media, emails, messaging, tracking

**Internet required**: Yes

---

### 15. 📝 BMI Calculator
**What it does**: Calculates Body Mass Index and health category.

**Inputs**:
- Weight (kg)
- Height (cm)

**BMI Categories**:
- **< 18.5**: Underweight
- **18.5 - 24.9**: Normal
- **25 - 29.9**: Overweight
- **≥ 30**: Obese

**Formula**: BMI = weight(kg) / (height(m))²

**Disclaimer**: For informational purposes, consult healthcare provider

---

## 🤖 AI Chatbot Features

### Capabilities
- Rule-based responses
- Context awareness
- Friendly personality
- Tool guidance
- Time/date information

### Sample Interactions
```
User: "Hi"
Bot: "Hello! 👋 How can I help?"

User: "What can you do?"
Bot: "I can chat, answer questions, and guide you through our tools!"

User: "What time is it?"
Bot: "Current time: 3:45:20 PM"

User: "Tell me about tools"
Bot: "We have 15+ tools — summarizer, translator, QR generator, calculator, and more!"
```

---

## 🎨 Interface Features

### Theme System
- **Dark Mode** (Default): Easy on eyes, modern aesthetic
- **Light Mode**: Professional appearance, high contrast
- **Toggle**: Click 🌙 button in navbar
- **Persistent**: Theme preference can be saved to localStorage

### Animations
- **Gradient background**: Smooth 15-second animation loop
- **Floating orbs**: 3D effect with staggered timing
- **Fade-up on load**: Smooth entrance animations
- **Tool cards**: Rise on hover, glow effect
- **Smooth scrolling**: Automatic scroll behavior

### Responsive Breakpoints
- **Desktop (1200px+)**: Full multi-column layout
- **Tablet (768px-1199px)**: Adjusted spacing
- **Mobile (<768px)**: Single column, touch-friendly

---

## 🔌 External APIs Used

### QRServer API
- **Endpoint**: `api.qrserver.com`
- **Purpose**: QR code generation
- **Rate limit**: Generous (free tier)
- **Fallback**: None (requires internet)

### MyMemory Translation API
- **Endpoint**: `api.mymemory.translated.net`
- **Purpose**: Language translation
- **Rate limit**: 5000 chars/day (free)
- **Languages**: 100+

### ExchangeRate API
- **Endpoint**: `api.exchangerate-api.com`
- **Purpose**: Currency conversion
- **Rate limit**: 1500 requests/month (free)
- **Update frequency**: Hourly

### TinyURL API
- **Endpoint**: `tinyurl.com/api-create.php`
- **Purpose**: URL shortening
- **Rate limit**: Unlimited
- **Redirect**: Permanent (301)

---

## 📊 Performance Metrics

### Load Time
- Initial load: < 2 seconds
- DOM ready: < 1 second
- Interactive: < 1.5 seconds

### Bundle Size
- HTML: ~200KB (single file)
- No external dependencies
- No build process required

### Browser Compatibility
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

---

## 🔐 Security & Privacy

### Data Handling
- All processing: Client-side only
- No data persistence: Except localStorage for theme
- No tracking: No analytics or cookies
- HTTPS: Recommended when deployed

### API Security
- Public APIs used (no authentication needed)
- Input sanitization on calculator
- No sensitive data transmitted

---

## 📝 Tips & Tricks

### Text Summarizer
- Works best with properly punctuated text
- Extracts first 2 sentences

### Password Generator
- Increase length for more security
- Copy immediately (not stored)

### QR Code
- Encode WiFi: `WIFI:T:WPA;S:ssid;P:password;;`
- Encode contact: Use vCard format

### Calculator
- Spaces are ignored
- Parentheses required for order of operations

### Translator
- Works best with complete sentences
- May need context for accuracy

---

*Last updated: 2026 | NeuroAI Team*
