# AvestaDate - Ancient Persian Calendar

![AvestaDate Logo](https://img.shields.io/badge/AvestaDate-Ancient%20Persian%20Calendar-ff6b35)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-deployed-green.svg)

A beautiful, interactive ancient Persian calendar web application that displays the traditional Zoroastrian calendar system with modern web technologies.

## 🌟 Features

### 📅 Ancient Persian Calendar
- **Traditional Date System**: Displays dates in the ancient Persian calendar format with historical month and day names
- **Synchronized with Modern Date**: Ancient dates are perfectly aligned with contemporary Gregorian calendar
- **Interactive Calendar Grid**: Monthly view with clickable days and today highlighting

### 🌅 Daily Content
- **365 Unique Morning Greetings**: A different ancient Persian morning message every day at 6 AM Iran time
- **Historical Events**: Display of ancient Persian and Pahlavi era events for each day
- **Daily Shahnameh Poetry**: A different verse from Ferdowsi's Shahnameh displayed each day with proper attribution

### 🎨 Modern UI/UX
- **Dark/Light Theme Toggle**: Switch between elegant dark and light themes
- **Bilingual Support**: Complete Persian (RTL) and English (LTR) language support
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Real-time Digital Clock**: Live clock showing Iran timezone

### 🔧 Technical Features
- **Pure Web Technologies**: Built with HTML5, CSS3, and Vanilla JavaScript
- **GitHub Pages Ready**: Optimized for deployment on GitHub Pages
- **No External Dependencies**: Completely self-contained application
- **Modern CSS**: Uses CSS Grid, Flexbox, and CSS Custom Properties
- **Smooth Animations**: Elegant transitions and hover effects

## 🚀 Live Demo

Visit the live application: [https://geekneuron.github.io/AvestaDate](https://geekneuron.github.io/AvestaDate)

## 📦 Installation & Setup

### Quick Start
1. **Clone the repository**:
   ```bash
   git clone https://github.com/GeekNeuron/AvestaDate.git
   cd AvestaDate
   ```

2. **Open in browser**:
   - Simply open `index.html` in your web browser
   - Or serve with a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

### GitHub Pages Deployment
1. **Fork or clone** this repository to your GitHub account
2. **Enable GitHub Pages** in repository settings
3. **Select source**: Choose `main` branch
4. **Access your site**: `https://yourusername.github.io/AvestaDate`

## 🏗️ Project Structure

```
AvestaDate/
├── index.html          # Main application file
├── README.md          # Project documentation
├── LICENSE            # MIT License
└── assets/            # (Optional) Future assets directory
    ├── images/        # Images and icons
    └── fonts/         # Custom fonts (if needed)
```

## 🎯 Usage Guide

### Language Toggle
- **Persian (فارسی)**: Default language with RTL layout
- **English**: Click the language toggle button to switch to English with LTR layout

### Theme Toggle
- **Dark Mode**: Default elegant dark theme
- **Light Mode**: Clean light theme for daytime use

### Calendar Navigation
- **Today Highlighting**: Current day is highlighted in the calendar
- **Interactive Days**: Click on any day to view specific information
- **Month Navigation**: Navigate through different months

### Daily Content
- **Morning Messages**: Special greetings appear at 6 AM Iran time
- **Historical Events**: Ancient Persian and Pahlavi era events
- **Poetry Section**: Daily verses from Shahnameh with attribution

## 🔧 Customization

### Adding More Content
1. **Morning Messages**: Edit the `morningMessages` array in the JavaScript section
2. **Historical Events**: Add events to the `ancientEvents` object
3. **Poetry Verses**: Expand the `shahnamehVerses` array
4. **Styling**: Modify CSS custom properties in the `:root` selector

### Color Scheme
The application uses CSS custom properties for easy theming:

```css
:root {
    --bg-primary: #0f0f0f;      /* Main background */
    --bg-secondary: #1a1a1a;    /* Secondary background */
    --bg-card: #252525;         /* Card backgrounds */
    --text-primary: #ffffff;     /* Primary text */
    --text-secondary: #b0b0b0;   /* Secondary text */
    --accent: #ff6b35;          /* Accent color */
    --accent-hover: #e55a2b;    /* Accent hover */
    --border: #333;             /* Border color */
    --shadow: rgba(0, 0, 0, 0.3); /* Shadow color */
}
```

## 🧮 Calendar System

The ancient Persian calendar used in this application is based on the traditional Zoroastrian calendar:

### Months (12 months)
1. **Farvardin** (فروردین) - 31 days
2. **Ordibehesht** (اردیبهشت) - 31 days
3. **Khordad** (خرداد) - 31 days
4. **Tir** (تیر) - 31 days
5. **Mordad** (مرداد) - 31 days
6. **Shahrivar** (شهریور) - 31 days
7. **Mehr** (مهر) - 30 days
8. **Aban** (آبان) - 30 days
9. **Azar** (آذر) - 30 days
10. **Dey** (دی) - 30 days
11. **Bahman** (بهمن) - 30 days
12. **Esfand** (اسفند) - 29 days (30 in leap years)

### Year Calculation
The ancient year calculation is synchronized with the modern calendar while maintaining historical accuracy.

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/amazing-feature`
3. **Commit your changes**: `git commit -m 'Add amazing feature'`
4. **Push to the branch**: `git push origin feature/amazing-feature`
5. **Open a Pull Request**

### Areas for Contribution
- 📝 **Content**: Add more historical events, poetry verses, or morning messages
- 🌐 **Localization**: Add support for more languages
- 🎨 **Design**: Improve UI/UX or add new themes
- 🔧 **Features**: Implement new calendar features or tools
- 📚 **Documentation**: Improve documentation or add tutorials

## 📜 Historical Background

The ancient Persian calendar system has roots in Zoroastrianism and was used throughout the Persian Empire. This application aims to preserve and present this cultural heritage in a modern, accessible format.

### Key Historical Points
- **Zoroastrian Origins**: Based on the religious calendar of ancient Persia
- **Cultural Significance**: Each month and day has symbolic meaning
- **Modern Relevance**: Still celebrated in Persian New Year (Nowruz) traditions

## 🐛 Known Issues & Roadmap

### Current Limitations
- Calendar conversion algorithm could be more historically accurate
- Limited historical events database
- Poetry collection needs expansion

### Future Enhancements
- [ ] More accurate historical date conversion
- [ ] Expanded events database
- [ ] Audio pronunciation for Persian terms
- [ ] Export/share functionality
- [ ] Mobile app version
- [ ] API for developers

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Ferdowsi**: For the eternal Shahnameh poetry
- **Ancient Persian Culture**: For the rich calendar system and traditions
- **Open Source Community**: For inspiration and tools
- **GitHub Pages**: For free hosting platform

## 📞 Contact & Support

- **Developer**: GeekNeuron
- **GitHub**: [@GeekNeuron](https://github.com/GeekNeuron)
- **Project Link**: [https://github.com/GeekNeuron/AvestaDate](https://github.com/GeekNeuron/AvestaDate)

For support, please open an issue on GitHub or contact the developer.

---

**Made with ❤️ for preserving Persian cultural heritage**

*"In the name of the Lord of soul and wisdom, whose thoughts are higher than
