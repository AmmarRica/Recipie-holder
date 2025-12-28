# 🍳 Recipe Holder

A simple, elegant HTML-based food recipe site that allows you to quickly create and format recipes with voice-to-text support. No backend required - works entirely in your browser!

## ✨ Features

- **📝 Text Input**: Easy-to-use form for recipe name, ingredients, and instructions
- **🎤 Voice-to-Text**: Record recipe details using your voice (Chrome/Edge browsers)
- **✨ Auto-Format**: Automatically formats ingredient lists into clean, organized lines
- **📋 Recipe Preview**: Beautiful formatted recipe display with numbered steps and checkmarked ingredients
- **📱 Responsive Design**: Works great on desktop, tablet, and mobile devices
- **🖨️ Print-Friendly**: Optimized for printing recipe cards
- **🚀 No Backend**: Pure HTML/CSS/JavaScript - works offline once downloaded

## 🎯 Usage

1. Open `index.html` in your web browser
2. Fill in the recipe details:
   - **Recipe Name**: Enter the name of your dish
   - **Ingredients**: Add ingredients (one per line or comma-separated)
   - **Instructions**: Enter cooking steps
3. Use voice recording buttons (🎤) to speak instead of typing
4. Click "Auto-Format List" to clean up your ingredients
5. Click "Save & Preview Recipe" to see your formatted recipe
6. Print or save the page for future reference

## 🎙️ Voice Recording

The voice-to-text feature uses the Web Speech API and works best in:
- Google Chrome (desktop and mobile)
- Microsoft Edge (desktop and mobile)

**Note**: Microphone permission is required. The browser will ask for permission when you first click a record button.

### How to Use Voice Recording:
1. Click any "🎤 Record" button
2. Allow microphone access when prompted
3. Speak clearly into your microphone
4. Click "⏹️ Stop Recording" when done
5. The text will appear in the corresponding field

## 🎨 Features in Detail

### Auto-Format Ingredients
The auto-format feature:
- Splits comma-separated or line-separated items
- Removes duplicate entries
- Cleans up numbering (1., 2., etc.) and bullet points (-, *, •)
- Creates a clean, one-ingredient-per-line format

### Recipe Preview
The preview displays:
- Recipe name as a prominent heading
- Ingredients with green checkmarks
- Instructions as numbered steps with circular badges
- Clean, professional layout perfect for printing

## 🛠️ Technical Details

- **HTML5**: Semantic markup with accessibility features
- **CSS3**: Modern styling with gradients, flexbox, and responsive design
- **JavaScript**: Vanilla JS for all functionality (no frameworks)
- **Web Speech API**: For voice-to-text conversion
- **No Dependencies**: Works without any external libraries

## 🔒 Security

- All user input is properly escaped to prevent XSS attacks
- No data is sent to any server (all processing is local)
- No cookies or tracking
- No external dependencies or CDN resources

## 📄 License

This project is open source and available for anyone to use and modify.

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for any improvements!

---

**Enjoy cooking and organizing your recipes! 👨‍🍳👩‍🍳**