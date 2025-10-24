#  Spotify Clone - Web Player

<div align="center">
  
  ![Spotify Clone](https://img.shields.io/badge/Spotify-Clone-1DB954?style=for-the-badge&logo=spotify&logoColor=white)
  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
  
  **A pixel-perfect Spotify UI clone built with pure HTML & CSS**
  
  [View Demo](#-demo) • [Features](#-features) • [Getting Started](#-getting-started) • [Screenshots](#-screenshots)
  
</div>

---

## 📖 Table of Contents

- [About The Project](#-about-the-project)
- [Demo](#-demo)
- [Features](#-features)
- [Built With](#️-built-with)
- [Screenshots](#-screenshots)
- [Folder Structure](#-folder-structure)
- [Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [What I Learned](#-what-i-learned)
- [Challenges Faced](#-challenges-faced)
- [Future Enhancements](#-future-enhancements)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)
- [Acknowledgments](#-acknowledgments)

---

## 🎯 About The Project

This is a **Spotify Web Player Clone** that replicates the visual design and layout of Spotify's web interface. Built as a mini-project during my Full Stack Development journey in the **Sigma Batch by Apna College**, this project showcases fundamental HTML and CSS skills without any backend functionality or AI assistance.

### 🎓 Learning Context

- **Course**: Full Stack Web Development - Sigma Batch
- **Institution**: Apna College
- **Focus**: HTML5 & CSS3 Fundamentals
- **Development Approach**: Hand-coded without framework dependencies
- **AI Usage**: Minimal (3-4 queries for loader functionality only)

### 💡 Project Motivation

The goal was to:
- ✅ Apply HTML & CSS concepts learned in the course
- ✅ Practice responsive design principles
- ✅ Recreate a production-grade UI from scratch
- ✅ Build pixel-perfect layouts using Flexbox
- ✅ Understand complex UI component structures

---

## 🎬 Demo

> **Note**: This is a UI-only clone. No audio playback or interactive features are implemented (no JavaScript functionality except for the loading animation).

🔗 **[Live Demo](https://msubham06.github.io/Spotify_Clone/)**

---

## ✨ Features

### 🎨 **UI Components**

| Component | Description |
|-----------|-------------|
| **Sidebar Navigation** | Home, Search, and Your Library sections |
| **Library Section** | Create Playlist & Browse Podcasts cards |
| **Sticky Navigation** | Backward/Forward navigation with user profile |
| **Content Cards** | Recently Played, Trending, and Featured Charts |
| **Music Player** | Bottom fixed player with album info and controls |
| **Custom Loading Screen** | Animated Spotify logo loader |
| **Responsive Design** | Mobile-friendly layout (breakpoints at 420px, 600px, 800px, 1000px, 1150px) |

### 🎨 **Design Features**

- ✅ **Pixel-Perfect Styling** - Matches Spotify's design language
- ✅ **Custom Scrollbars** - Styled to blend seamlessly
- ✅ **Hover Effects** - Interactive visual feedback
- ✅ **Progress Bars** - Custom-styled range inputs for playback/volume
- ✅ **Font Integration** - Montserrat & Poppins from Google Fonts
- ✅ **Icon Library** - Font Awesome 7.0.1 integration
- ✅ **Dark Theme** - True-to-original Spotify black theme

---

## 🛠️ Built With

<table>
  <tr>
    <td align="center" width="150">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="50" height="50" alt="HTML5"/>
      <br><b>HTML5</b>
    </td>
    <td align="center" width="150">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="50" height="50" alt="CSS3"/>
      <br><b>CSS3</b>
    </td>
    <td align="center" width="150">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="50" height="50" alt="JavaScript"/>
      <br><b>JavaScript</b><br>(Loader only)
    </td>
  </tr>
</table>

### **Technologies & Libraries**

- **HTML5** - Semantic markup structure
- **CSS3** - Flexbox, custom properties, animations
- **JavaScript** - Minimal (page loader only)
- **Font Awesome 7.0.1** - Icon library
- **Google Fonts** - Montserrat & Poppins

---

## 📸 Screenshots

### 🖥️ Desktop View

![Alt text](assets\desktop-view.png)

### 📱 Mobile View (< 600px)

![Alt text](assets\mobile-view.png)

## 📂 Folder Structure

```
spotify-clone/
│
├── index.html              # Main HTML file
├── style.css               # All styling (1000+ lines)
├── README.md               # Project documentation
│
└── assets/                 # Image assets
    ├── logo.png           # Spotify logo
    ├── backward_icon.png  # Navigation icons
    ├── forward_icon.png
    ├── library_icon.png
    ├── player_icon1.png   # Player control icons
    ├── player_icon2.png
    ├── player_icon3.png
    ├── player_icon4.png
    ├── player_icon5.png
    ├── card1img.jpeg      # Playlist card images
    ├── card2img.jpeg
    ├── card3img.jpeg
    ├── card4img.jpeg
    ├── card5img.jpeg
    ├── card6img.jpeg
    ├── card7img.jpg       # Album cover (music player)
    ├── card8img.jpg
    ├── card9img.png
    └── card10img.png
```


## 📚 What I Learned

Building this project reinforced several key concepts:

### HTML5 Concepts
- ✅ Semantic HTML structure (`<nav>`, `<section>`, `<footer>`)
- ✅ Proper meta tags for viewport and charset
- ✅ External resource linking (fonts, icons, stylesheets)
- ✅ Organizing complex nested structures
- ✅ Accessibility considerations (alt texts, labels)

### CSS3 Techniques
- ✅ **Flexbox Mastery** - Building complex layouts without Grid
- ✅ **Custom Properties** - CSS variables for theme consistency
- ✅ **Pseudo-classes** - `:hover`, `:focus`, `:active` states
- ✅ **Media Queries** - Responsive breakpoints (420px to 1150px)
- ✅ **Custom Styling** - Range inputs, scrollbars, and progress bars
- ✅ **CSS Animations** - Fade pulse effect for loader
- ✅ **Positioning** - `sticky`, `fixed`, `relative`, `absolute`
- ✅ **Overflow Management** - Custom scrollbar styling
- ✅ **Gradient Backgrounds** - Linear gradients for progress indicators

### JavaScript Basics
- ✅ Window event listeners (`load` event)
- ✅ DOM manipulation (class toggling)
- ✅ setTimeout for delayed actions
- ✅ Basic animation timing

### Design Principles
- ✅ **Visual Hierarchy** - Using size, color, and spacing
- ✅ **Consistency** - Maintaining design patterns throughout
- ✅ **Whitespace** - Proper spacing for readability
- ✅ **Color Theory** - Dark theme implementation
- ✅ **Typography** - Font pairing and sizing
- ✅ **User Experience** - Hover states and visual feedback

---

## 🏔️ Challenges Faced

Building this clone presented several learning opportunities:

### 1. **Responsive Sidebar**
**Challenge**: Making sidebar disappear on mobile while keeping content accessible.

**Solution**: Used `@media (max-width: 600px)` to hide sidebar with `display: none`.

### 2. **Custom Range Inputs**
**Challenge**: Styling the progress bar and volume slider to match Spotify's design.

**Solution**: Used `-webkit-slider-thumb` and `-webkit-slider-runnable-track` pseudo-elements with custom gradients.

```css
.progress-bar::-webkit-slider-thumb {
  appearance: none;
  width: 0.6rem;
  height: 0.6rem;
  border-radius: 50%;
  background-color: #1bd760;
}
```

### 3. **Sticky Navigation**
**Challenge**: Keeping navigation visible while scrolling through playlists.

**Solution**: Implemented `position: sticky; top: 0;` with proper z-index layering.

### 4. **Loading Animation**
**Challenge**: Creating smooth fade-in effect for page content.

**Solution**: CSS opacity transitions combined with JavaScript event listeners:

```javascript
window.addEventListener('load', () => {
  const loader = document.getElementById('loader');
  loader.classList.add('hidden');
  setTimeout(() => loader.remove(), 600);
});
```

### 5. **Multiple Breakpoints**
**Challenge**: Managing layout across 5+ different screen sizes.

**Solution**: Strategic media queries at 420px, 600px, 800px, 1000px, and 1150px with conditional displays.

---

## 🔮 Future Enhancements

While this is currently a UI-only clone, potential improvements include:

### Phase 1 - Interactivity (JavaScript)
- [ ] Add play/pause functionality
- [ ] Implement working progress bar (seek functionality)
- [ ] Volume control slider
- [ ] Search functionality with filtering
- [ ] Card click navigation
- [ ] Dynamic playlist loading

### Phase 2 - Backend Integration
- [ ] Connect to Spotify Web API
- [ ] User authentication (OAuth)
- [ ] Fetch real playlist data
- [ ] Stream audio tracks
- [ ] Save user preferences
- [ ] Create custom playlists

### Phase 3 - Advanced Features
- [ ] Dark/Light theme toggle
- [ ] Keyboard shortcuts
- [ ] Lyrics display
- [ ] Queue management
- [ ] Share functionality
- [ ] Offline mode (PWA)

### Phase 4 - Performance
- [ ] Lazy loading for images
- [ ] Code splitting
- [ ] Service Worker implementation
- [ ] Accessibility improvements (ARIA labels)

---


## 📄 License

This project is for **educational purposes only**. It is not affiliated with or endorsed by Spotify.

- The Spotify name, logo, and design are trademarks of **Spotify AB**.
- This project is created purely for learning HTML/CSS and portfolio demonstration.
- Not intended for commercial use or distribution.

**MIT License** - You're free to use this code for learning and personal projects.

---

## 📞 Contact

<div align="center">

**Hello! I'm Subham**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/msubham/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MSubham06)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/irl.subhhh?igsh=Znl4anBoMnhvNWhs)

**Project Link**: [https://github.com/MSubham06/spotify-clone](https://github.com/MSubham06/spotify-clone)

</div>

---

## 🙏 Acknowledgments

Special thanks to:

- **[Apna College](https://www.apnacollege.in/)** - For the amazing Full Stack Web Development course (Sigma Batch)
- **[Spotify](https://open.spotify.com/)** - For the inspiration and design reference
- **[Font Awesome](https://fontawesome.com/)** - For the comprehensive icon library
- **[Google Fonts](https://fonts.google.com/)** - For Montserrat and Poppins fonts
- **[Shradha](https://www.instagram.com/shradhakhapra/#)** - For teaching HTML & CSS fundamentals 

### Resources Used

- [MDN Web Docs](https://developer.mozilla.org/) - CSS reference
- [CSS-Tricks](https://css-tricks.com/) - Flexbox guides
- [Stack Overflow](https://stackoverflow.com/) - Community support
- [ChatGPT](https://chat.openai.com/) - Loader functionality clarification (3-4 queries)

---

<div align="center">

### ⭐ Star this repo if you found it helpful!

**Made with ❤️ by Subham**

[The Real OG: Spotify](https://open.spotify.com/)

---

**© 2025 Subham | Full Stack Development Journey**


</div>
