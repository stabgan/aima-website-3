# AIMA Exercises Website

A modern, responsive web interface for Artificial Intelligence: A Modern Approach (AIMA) textbook exercises, featuring Material Design-inspired styling and mathematical notation support.

## 🎯 What It Does

This website provides an interactive platform for students and educators to access exercises from the AIMA textbook. It presents complex AI concepts and problems in a clean, accessible format with proper mathematical notation rendering through MathJax.

### Key Features

- **Interactive Exercise Browser**: Navigate through AI topics from basic introduction to advanced concepts
- **Mathematical Notation**: Full LaTeX/MathJax support for complex formulas and logical expressions  
- **Responsive Design**: Material Design-inspired interface that works on all devices
- **Structured Learning Path**: Organized by AIMA textbook chapters and sections

## 🛠 Tech Stack

| Technology | Purpose | Version |
|------------|---------|---------|
| 🌐 **HTML5** | Structure & Content | Latest |
| 🎨 **CSS3** | Material Design Styling | Latest |
| 📱 **Bootstrap** | Responsive Grid System | 4.x |
| 🧮 **MathJax** | Mathematical Notation | 2.7.2 |
| ⚡ **jQuery** | DOM Manipulation | 3.6.0 |

## 📚 Content Coverage

The website currently includes exercises for:

### I. Artificial Intelligence
- ✅ **Introduction** - Fundamental AI concepts and definitions
- 🔗 **Intelligent Agents** - Agent architectures and rationality

### III. Knowledge, Reasoning and Planning  
- ✅ **Logical Agents** - Propositional logic and knowledge representation

### Additional Sections (Planned)
- Problem-Solving & Search
- Constraint Satisfaction
- Uncertainty & Probabilistic Reasoning
- Machine Learning
- Natural Language Processing
- Robotics & Perception

## 🚀 Getting Started

### Prerequisites
- Modern web browser with JavaScript enabled
- Internet connection (for CDN resources)

### Installation & Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/stabgan/aima-website-3.git
   cd aima-website-3
   ```

2. **Serve locally** (optional):
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Or simply open index.html in your browser
   ```

3. **Access the website**:
   - Local: `http://localhost:8000`
   - Live: [https://stabgan.github.io/aima-website-3](https://stabgan.github.io/aima-website-3)

## 🎨 Design Philosophy

The interface follows Google's Material Design principles:
- **Clean Typography**: Multiple font families for hierarchy and readability
- **Card-Based Layout**: Exercises presented in elevated card components
- **Responsive Grid**: Bootstrap-powered responsive design
- **Subtle Animations**: CSS transitions for smooth interactions
- **Consistent Shadows**: Depth and elevation through shadow systems

## 📖 Usage Guide

1. **Browse Topics**: Start from the main page table of contents
2. **Navigate Exercises**: Use the sidebar navigation in exercise pages
3. **Mathematical Content**: All formulas render automatically via MathJax
4. **Search**: Use the search functionality to find specific topics

## 🔧 Development

### File Structure
```
├── index.html              # Main landing page
├── intro_exercise_card.html # Introduction exercises
├── knowledge_logic_card.html # Logic exercises with MathJax
├── css/
│   ├── bootstrap*.css      # Bootstrap framework
│   ├── cards.css          # Main page styling
│   └── cards-exercise.css  # Exercise page styling
└── js/
    └── bootstrap*.js       # Bootstrap JavaScript
```

### Key Components
- **Responsive Navigation**: Fixed sidebar with smooth scrolling
- **MathJax Integration**: Configured for inline and display math
- **Card System**: Modular exercise presentation
- **Search Interface**: Placeholder for future search functionality

## ⚠️ Known Issues

- **Limited Content**: Only Introduction and Logical Agents exercises are fully implemented
- **Search Functionality**: Search form present but not yet functional
- **Mobile Navigation**: Sidebar navigation could be improved for mobile devices
- **Exercise Links**: Many navigation links point to placeholder pages

## 🤝 Contributing

Contributions are welcome! Areas for improvement:
- Add remaining AIMA exercise content
- Implement search functionality  
- Improve mobile responsiveness
- Add interactive problem-solving tools
- Enhance accessibility features

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Kaustabh Ganguly**
- GitHub: [@kaustabhganguly](https://github.com/kaustabhganguly)
- Original Design & Implementation

---

*Built with ❤️ for the AI education community*