A Love Story based website 

An interactive, image-centric photo carousel website celebrating a beautiful love story. Built with HTML5, CSS3, and vanilla JavaScript using Bootstrap 5.

## 🌟 Features

- **30-Slide Interactive Carousel** - A complete narrative of a romantic journey
- **Image-Focused Design** - Large, stunning photos with minimal overlay text
- **Creative Navigation**
  - 🔘 Animated dot indicators at the bottom
  - ↓ Scroll hints on the right side with pulsing animations
  - ⌨️ Keyboard navigation (arrow keys)
  - 🖱️ Mouse wheel scrolling
  - 📱 Touch-friendly carousel for mobile devices
- **Responsive Design** - Optimized for all devices (iPhone 16, Android phones, tablets, desktops)
- **Mobile-First** - Safe area support for notched devices
- **Animations** - Smooth transitions, fade-ins, and pulsing effects
- **Audio Soundtrack** - Background music with smart autoplay handling
- **Glassmorphism Effects** - Modern backdrop blur and gradient overlays

## 📱 Device Support

- ✅ iPhone 16 (and other iPhones with notch)
- ✅ CMF Nothing 2 Pro & Android phones
- ✅ Tablets (iPad, Android tablets)
- ✅ Desktop browsers
- ✅ Landscape orientation support

## 🎨 Design Highlights

- **Minimal Text Overlay** - Images are the primary focus (max-height: 28vh caption)
- **Color-Coded Messages** - Makers's messages in blue, Special person's in pink
- **Scene Descriptions** - Poetic descriptions for each slide
- **Slide Counter** - Top-right counter showing current position (e.g., 5/30)
- **Gradient Backgrounds** - Beautiful gradients transitioning from black to transparent

## 🎮 Navigation Options

### Keyboard
- `→` / `←` Arrow keys to navigate slides
- Works on all devices with keyboard support

### Mouse & Trackpad
- Scroll wheel up/down to navigate
- Click animated dots to jump to any slide
- Hover effects on all interactive elements

### Touch
- Swipe on carousel (Bootstrap touch support)
- Tap dots to jump to slides
- All touch targets optimized for mobile

## 📁 Project Structure

```
ProjectDEC26/
├── index.html                 # Main carousel website
├── bootstrap/                 # Bootstrap 5 framework
│   ├── css/                   # CSS files
│   └── js/                    # JavaScript files
├── Photos/                    # 30 images (1.jpg - final.jpg)
│   ├── 1.jpg - 11.jpeg       # Nature and location photos
│   ├── WhatsApp Images/       # Personal moment photos
│   ├── final.jpg             # Closing image
│   └── soundtrack.mp3        # Background music
└── README.md                 # This file
```

## 🚀 Getting Started

### Option 1: Local Development
```bash
# Clone the repository
git clone https://github.com/arkabera2004/ProjectDEC26.git
cd ProjectDEC26

# Start a local server (Python)
python3 -m http.server 8000

# Open in browser
open http://localhost:8000
```

### Option 2: Direct Opening
Simply double-click `index.html` to open in your default browser (works offline).

## 💻 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Advanced animations, gradients, backdrop filters
- **JavaScript** - Vanilla JS (no jQuery or other libraries)
- **Bootstrap 5** - Carousel component and responsive grid
- **CSS Animations** - fadeInUp, slideIn, pulse, floatUp

## 🎯 Key Code Features

### Responsive Layout
- Fluid typography using `clamp()`
- Safe area support for notched devices with `env(safe-area-inset-*)`
- Multiple media queries for different screen sizes

### JavaScript Functionality
```javascript
// Bootstrap Carousel initialization
new bootstrap.Carousel(carousel, { interval: false, wrap: true })

// Keyboard navigation
document.addEventListener('keydown', handleArrowKeys)

// Wheel scrolling
document.addEventListener('wheel', handleScrollNavigation)

// Device detection
detectDevice() // Adds device-specific classes
```

### CSS Animations
- `@keyframes fadeInUp` - Text entrance animation
- `@keyframes slideIn` - Image transition
- `@keyframes pulse` - Dot and scroll hint animation
- `@keyframes floatUp` - Floating entrance effect

## 📱 Mobile Optimizations

- **Viewport Fit** - Covers notch on iPhone
- **Safe Area Insets** - Respects device safe areas
- **Touch Optimization** - Tap-highlight removed, touch-callout disabled
- **User Select** - Disabled for cleaner UX
- **Responsive Units** - Uses clamp() for fluid scaling
- **Landscape Support** - Special styling for landscape orientation

## 🎵 Audio

- `soundtrack.mp3` - Background music
- Auto-mutes on first load (respects browser autoplay policy)
- Unmutes on user interaction
- Loops continuously

## 🔄 Navigation States

### Dot Indicators
- Small dots (6px) for non-active slides
- Expand to 18px width when active
- Pink glow effect on active dot
- Hover effects for better UX

### Scroll Hints
- Right-side arrow with pulsing animation
- Vertical "SCROLL" text
- Changes to "↑ START" on final slide
- Fades out on hover for clean view

## 🎭 Story Structure

The carousel tells a complete love story across 30 slides:

1. **Slides 1-11** - Initial journey and promises
2. **Slides 12-26** - Growth, trust, and commitment
3. **Slides 27-30** - Birthday celebration and forever promise

Each slide features:
- Beautiful background image
- Poetic scene description
- Conversation between two people with color-coded messages
- Emoji title
- Minimal overlay for maximum photo visibility

## 🌐 Browser Compatibility

- ✅ Chrome/Chromium (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## ⚙️ Customization

### Change the Story
Edit the slide content in `index.html`:
```html
<div class="message arka">
    <div class="message-label">Arka</div>
    Change this text to customize the story
</div>
```

### Change Colors
Modify CSS variables in `<style>`:
```css
.message.arka {
    background: linear-gradient(135deg, rgba(100, 150, 255, 0.2), ...);
}
```

### Change Images
Replace files in `Photos/` folder:
- Keep same filenames (1.jpg, 2.jpg, etc.)
- Or update `src` attributes in HTML

### Change Music
Replace `Photos/soundtrack.mp3` with your audio file

## 📝 License

Created with love. Feel free to use as inspiration for your own projects!

## 💌 About

This project is a romantic photo carousel telling the complete love story of Arka and Samadrita. Created as a memorable gift with carefully curated images and meaningful conversations.

---

**Made with Arka Bera** | 
View live: https://github.com/arkabera2004/ProjectDEC26
