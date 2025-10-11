# Interactive Teacher Toolkits

A comprehensive web-based educational toolkit featuring an interactive quiz creator with multiple difficulty levels and a full-featured digital whiteboard for teaching.

Created with assistance from DeepSeek V3.1, GPT-5 and Claude Sonnet 4.5.

## 🌟 Features

### Quiz Creator
- **Custom Quiz Creation**: Create quizzes with multiple difficulty levels
- **Rich Media Support**: Add images, videos, and audio to questions and after-answer sections
- **Custom Sound Effects**: Upload custom sounds for correct/incorrect answers per level
- **Level Management**: Create custom levels with names and gradient colors
- **Import/Export**: Save and load quizzes using browser localStorage

### Digital Whiteboard
- **Drawing Tools**: Pen, highlighter, eraser with customizable colors and thickness
- **Shape Tools**: Rectangle, circle, ellipse, line, triangle, arrow, pentagon
- **Text Tool**: In-place text editor with resizable text boxes
- **PDF Support**: Import PDFs with page navigation and per-page annotations
- **Image Import**: Import images as background
- **Pan & Zoom**: Ctrl+Wheel to zoom, Wheel to pan
- **Split Screen Mode**: Show reference content alongside whiteboard
- **Quick Access Toolbar**: Easy access to common tools

## 📁 Project Structure

```
Quiz-Creator/
│
├── menu.html               # 🚪 START HERE - Main entry point
│
├── pages/                  # Application pages
│   ├── index.html         # Quiz player
│   ├── create_quiz.html   # Quiz creation interface
│   ├── whiteboard.html    # Digital whiteboard
│   └── debug_quiz.html    # Quiz data debugger
│
├── css/
│   └── styles.css         # Main stylesheet
│
├── js/
│   ├── script.js          # Quiz player logic
│   └── admin.js           # Quiz creation logic
│
├── docs/
│   └── OPTIMIZATION_NOTES.md
│
├── .gitignore
├── LICENSE
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, or Edge)
- No server required - runs completely in the browser!

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/quiz-creator.git
cd quiz-creator
```

2. Open `menu.html` in your web browser

### Usage

#### Creating a Quiz
1. Click "Quiz Creator" from main menu
2. Enter quiz name and create levels
3. Add questions with media support
4. Upload custom sounds for correct/incorrect answers
5. Data auto-saves to browser localStorage

#### Using the Whiteboard
1. Click "Digital Whiteboard" from main menu
2. Select tools from left sidebar
3. Import PDFs for annotation
4. Use quick-access toolbar for common tools
5. Export as PNG when done

## 🎨 Key Features

### Quiz Features
- Multi-level support with custom names and colors
- Media-rich questions (images, videos, audio)
- After-answer media display (2-second delay)
- Custom sounds per level
- Persistent localStorage storage

### Whiteboard Features
- **PDF Support**: Per-page annotations, navigation controls, auto-fit
- **Shape Tools**: All shapes resizable and moveable
- **Text Editor**: In-place editing with resizable boxes
- **Split-Screen**: UI repositions automatically
- **Pen Settings**: Independent thickness controls for pen and eraser

## 🛠️ Technical Details

- **Technologies**: HTML5, CSS3, Vanilla JavaScript
- **PDF Rendering**: PDF.js
- **Storage**: localStorage API
- **Icons**: Font Awesome 6.4.0
- **100% client-side** - no backend needed

## 📝 Browser Compatibility

- Chrome/Edge: ✅ Fully supported
- Firefox: ✅ Fully supported
- Safari: ✅ Fully supported
- Mobile: ⚠️ Limited (desktop recommended)

## 🤝 Contributing

Contributions welcome! Feel free to submit a Pull Request.

## 📄 License

MIT License - feel free to use and modify!

## 🐛 Known Issues

- Mobile touch support limited
- Large PDFs may be slow to render
- localStorage size limits (5-10MB typical)

## 🔮 Future Enhancements

- Export/import quiz JSON files
- Cloud storage integration
- Touch/stylus optimization
- Quiz analytics and tracking
- Whiteboard collaboration

---

**Happy teaching and learning! 🎓✨**
