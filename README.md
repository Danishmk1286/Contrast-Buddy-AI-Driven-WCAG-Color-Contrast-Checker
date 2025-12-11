# 🎨 Contrast Buddy: AI-Driven WCAG Color Contrast Checker

<div align="center">

![WCAG 2.2 Compliant](https://img.shields.io/badge/WCAG-2.2-22C55E?style=for-the-badge&logo=accessibility&logoColor=white)
![React](https://img.shields.io/badge/React-18.2-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen?style=for-the-badge)

**Stop guessing. Start building accessible designs that everyone can use.**

[🚀 Live Demo]([](https://thecolorcontrastchecker.com) • [📖 Documentation](#features) • [🤝 Contribute](#contributing) • [🐛 Report Bug](https://github.com/yourusername/contrast-buddy/issues)

</div>

---

## 🔥 Why This Matters: The Accessibility Crisis You're Solving

**1 in 4 adults in the US has a disability.** That's **61 million people** who might struggle to read your website if your color contrast is insufficient.

### The Real Cost of Poor Contrast

- **Legal Risk**: Companies like Domino's, Target, and Netflix have faced accessibility lawsuits costing millions
- **Lost Revenue**: 15% of the global population has some form of disability - that's potential customers you're excluding
- **SEO Impact**: Search engines favor accessible websites, affecting your rankings
- **Brand Reputation**: Inaccessible designs signal that you don't care about all users

### Why Traditional Tools Fall Short

Most contrast checkers tell you what's wrong but **don't help you fix it**. You're left guessing which colors will work, wasting hours tweaking hex values manually.

**Contrast Buddy solves this** by providing AI-powered suggestions that maintain your design aesthetic while ensuring WCAG 2.2 compliance.

---

## ✨ What Makes This Different?

### 🧠 AI-Powered Intelligence
Get smart color suggestions that preserve your design intent. Our AI understands color theory and suggests alternatives that keep your brand identity intact.

### ⚡ Zero Backend Required
Works entirely in the browser. No server, no database, no API calls needed for core functionality. Deploy anywhere, instantly.

### 🎯 Real-Time Feedback
See your contrast ratio update instantly as you adjust colors. No page refreshes, no waiting.

### 🎨 Beautiful, Modern UI
A polished interface that developers and designers actually want to use. Built with attention to detail and smooth animations.

### 📱 Fully Responsive
Works flawlessly on desktop, tablet, and mobile devices.

---

## 🚀 Features

| Feature | Description |
|---------|-------------|
| **WCAG 2.2 Compliance** | Full support for the latest WCAG 2.2 guidelines with AA and AAA level checking |
| **AI-Powered Suggestions** | Get intelligent color alternatives that maintain your design aesthetic |
| **Smart Fallback** | Works without AI using algorithmic suggestions - no API key required |
| **Real-Time Preview** | See exactly how your text looks on your background color |
| **One-Click Swap** | Instantly swap foreground and background colors |
| **Comprehensive Testing** | Tests both normal and large text for AA and AAA compliance |
| **Zero Dependencies** | Pure React + Vite - lightweight and fast |
| **Accessible by Design** | Built with accessibility in mind, following best practices |

---

## 📸 Preview

![Demo](public/demo.gif)

*See your contrast ratio, compliance status, and get AI-powered suggestions in seconds.*

---

## 🛠️ Quick Start

### Prerequisites

- Node.js 16+ and npm/yarn/pnpm

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/contrast-buddy.git
cd contrast-buddy

# Install dependencies
npm install

# Start development server
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### Build for Production

```bash
npm run build
```

The optimized build will be in the `dist` folder, ready to deploy anywhere.

---

## 🎯 Usage

1. **Enter Colors**: Use the color picker or type hex values for text and background colors
2. **View Results**: Instantly see your contrast ratio and WCAG compliance status
3. **Get Suggestions**: Click "Get AI Fix Suggestions" if your contrast fails
4. **Apply Changes**: Click any suggestion to apply it instantly
5. **Swap Colors**: Use the swap button to quickly reverse foreground and background

### AI Configuration (Optional)

The app works perfectly without any configuration using smart algorithmic suggestions.

To enable AI-powered suggestions via OpenAI:

1. Copy `.env.example` to `.env`
2. Add your OpenAI API key:

```env
VITE_AI_API_KEY=your-openai-api-key
VITE_AI_API_URL=https://api.openai.com/v1/chat/completions
```

---

## 📊 WCAG 2.2 Contrast Requirements

| Level | Normal Text (≤18pt) | Large Text (≥18pt or ≥14pt bold) |
|-------|---------------------|-----------------------------------|
| **AA** | 4.5:1 | 3:1 |
| **AAA** | 7:1 | 4.5:1 |

**Large text** is defined as:
- 18pt (24px) or larger for regular text
- 14pt (18.67px) or larger for bold text

---

## 🏗️ Tech Stack

- **React 18** - Modern UI library
- **Vite 5** - Lightning-fast build tool
- **Pure CSS** - No framework dependencies, full control
- **OpenAI API** (Optional) - For AI-powered suggestions

---

## 🤝 Contributing

We **love** contributions! This project thrives on community input. Here's how you can help:

### Why Contribute?

- **Build Your Portfolio**: Showcase your skills in accessibility, React, and modern web development
- **Learn Best Practices**: Work with clean, modern code following industry standards
- **Make an Impact**: Help make the web more accessible for millions of users
- **Join a Community**: Connect with developers and designers passionate about accessibility

### How to Contribute

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/amazing-feature`)
3. **Make your changes** (see [contribution guidelines](CONTRIBUTING.md))
4. **Commit your changes** (`git commit -m 'Add amazing feature'`)
5. **Push to the branch** (`git push origin feature/amazing-feature`)
6. **Open a Pull Request**

### Areas We'd Love Help With

- 🌍 **Internationalization**: Add support for multiple languages
- 🎨 **Design Improvements**: Enhance the UI/UX with your creative ideas
- 🧪 **Testing**: Add unit tests, integration tests, or E2E tests
- 📱 **Mobile Enhancements**: Improve mobile experience
- 🔧 **New Features**: 
  - Color palette import/export
  - Browser extension
  - Figma/Adobe XD plugin
  - Batch color checking
  - Color blindness simulation
  - History/undo functionality
- 📚 **Documentation**: Improve docs, add examples, create tutorials
- 🐛 **Bug Fixes**: Help us squash bugs and improve stability
- ⚡ **Performance**: Optimize rendering, reduce bundle size

### Contribution Guidelines

- Follow the existing code style
- Write meaningful commit messages
- Add comments for complex logic
- Test your changes thoroughly
- Update documentation as needed

---

## 🌟 Roadmap

- [ ] Browser extension (Chrome, Firefox, Safari)
- [ ] Figma plugin integration
- [ ] Color palette import/export (JSON, CSS, SCSS)
- [ ] Batch color checking
- [ ] Color blindness simulation modes
- [ ] History/undo functionality
- [ ] PWA support for offline use
- [ ] Dark/light theme toggle
- [ ] Multiple language support
- [ ] Advanced color theory suggestions
- [ ] Integration with design tools

**Have an idea?** [Open an issue](https://github.com/yourusername/contrast-buddy/issues) and let's discuss!

---

## 📈 Impact & Statistics

- **WCAG 2.2 Compliant**: Follows the latest accessibility guidelines
- **Zero Backend**: No server costs, no data privacy concerns
- **Fast**: Loads in milliseconds, works offline
- **Lightweight**: Minimal bundle size, optimized for performance

---

## 🎓 Learning Resources

### Understanding WCAG

- [WCAG 2.2 Quick Reference](https://www.w3.org/WAI/WCAG22/quickref/)
- [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/)
- [A11y Project](https://www.a11yproject.com/)

### Color Theory

- [Color Contrast for Accessibility](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum.html)
- [Understanding Color Contrast](https://www.smashingmagazine.com/2014/10/color-contrast-tips-and-tools-for-accessibility/)

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- WCAG guidelines by W3C
- OpenAI for AI capabilities
- The accessibility community for inspiration and feedback

---

## 💬 Get in Touch

- 🐛 [Report a Bug](https://github.com/yourusername/contrast-buddy/issues)
- 💡 [Request a Feature](https://github.com/yourusername/contrast-buddy/issues)
- 💬 [Discussions](https://github.com/yourusername/contrast-buddy/discussions)

---

<div align="center">

**Made with ❤️ for an accessible web**

[⭐ Star this repo](https://github.com/yourusername/contrast-buddy) if you find it helpful!

[🔀 Fork it](https://github.com/yourusername/contrast-buddy/fork) and make it your own!

[🤝 Contribute](https://github.com/yourusername/contrast-buddy/blob/main/CONTRIBUTING.md) and help make the web more accessible!

</div>

---

## 🔍 SEO Keywords

*WCAG 2.2, color contrast checker, accessibility tool, web accessibility, a11y, contrast ratio calculator, WCAG compliance, accessible design, color accessibility, contrast checker tool, AI color suggestions, web design accessibility, color contrast analyzer, WCAG AA AAA, accessible color palette, color contrast tool, design accessibility, web accessibility checker, color contrast validator, accessible web design*
