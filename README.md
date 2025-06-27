# Save-Time UX - Screen Time Review Dashboard

A clean, visual interface for reviewing daily screen time limits 2. Add corresponding CSS styling
3. Update JavaScript logic for threshold checking

## 🙏 Acknowledgmentstreaming and social media platforms.

## 🎯 Overview

Save-Time UX is a minimalist web application that helps users visualize their daily usage limits for entertainment platforms. The app provides instant visual feedback about whether you're staying within your set time boundaries for platforms like Reddit, YouTube, Netflix, and Prime Video.

## ✨ Features

### 📱 **Clean Mobile Interface**
- Designed with a mobile-first approach (414x896px viewport)
- Modern gradient background with intuitive card-based layout
- Professional typography using Montserrat font family

### ⏱️ **Real-Time Usage Monitoring**
- **Reddit**: 3-hour daily limit
- **YouTube**: 1-hour daily limit  
- **Netflix**: 2-hour daily limit
- **Prime Video**: 30-minute daily limit

### 🎨 **Visual Status Indicators**
- **Green**: Usage within healthy limits
- **Red**: Exceeded recommended time limits
- Interactive "CHECK" button for instant status updates

### 🖼️ **Platform Integration**
- Official logos and branding for each platform
- Recognizable icons for easy platform identification
- Consistent visual hierarchy across all time cards

## 🛠️ Technical Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Design**: Mobile-responsive layout with CSS Flexbox/Grid
- **Styling**: Custom CSS with modern design principles
- **Interactivity**: DOM manipulation for real-time status updates

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Save-Time-UX.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Save-Time-UX
   ```

3. Open `index.html` in your web browser or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

## 📱 How to Use

1. **Open the Application**: Load `index.html` in your browser
2. **Review Current Usage**: View your current daily usage for each platform
3. **Check Status**: Click the "CHECK" button to see visual status indicators
4. **Interpret Results**:
   - 🟢 **Green**: You're within your healthy usage limits
   - 🔴 **Red**: Time to take a break - you've exceeded recommended limits

## 📁 Project Structure

```
Save-Time-UX/
├── index.html          # Main application file
├── stylesheet.css      # Styling and layout
├── README.md          # Project documentation
└── img/               # Platform logos and icons
    ├── back.svg
    ├── check.jpg
    ├── Ellipse.png
    ├── menu.svg
    ├── netflix-logo.png
    ├── prime-logo.png
    ├── reddit-logo.png
    └── youtube logo.png
```

## 🎨 Design Philosophy

This application follows modern UX principles:
- **Minimalism**: Clean interface without distractions
- **Accessibility**: High contrast colors and readable typography
- **Instant Feedback**: Immediate visual responses to user actions
- **Mobile-First**: Optimized for smartphone usage patterns

## 🔧 Customization

### Modifying Time Limits
Edit the JavaScript thresholds in `index.html`:
```javascript
// Current limits (in hours)
if(timecolor >= 3)     // Reddit: 3 hours
if(timecolor1 >= 3)    // YouTube: 1 hour (displayed as 1)
if(timecolor2 >= 2)    // Netflix: 2 hours
if(timecolor3 >= 3)    // Prime Video: 0.5 hours
```

### Adding New Platforms
1. Add new logo to `/img/` folder
2. Create HTML elements following the existing pattern
3. Add corresponding CSS styling
4. Update JavaScript logic for threshold checking

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Platform logos are property of their respective companies
- Montserrat font family by Google Fonts
- Inspired by digital wellness and mindful technology usage

---

**Built with ❤️ for healthier digital habits**


