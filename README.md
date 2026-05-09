# ChronoFlip ⏱️

**[Live Demo: ChronoFlip](https://itsadityakr.github.io/ChronoFlip/)**

ChronoFlip is a highly customizable, beautiful, fullscreen digital clock built with React and Vite. It features fluid scaling, multiple animation engines (including mechanical flip cards and odometer dials), and stunning dynamic themes ranging from minimalist wireframes to immersive video backgrounds.

---

## ✨ Features

- **Dual Animation Engines:** Choose between classic mechanical **Flip Card** animations or smooth **Odometer (Dial)** scrolling.
- **Immersive Themes:** Multiple hand-crafted themes:
  - 🌙 **Classic Dark & Light**
  - 🖤 **Pure B&W:** A high-contrast wireframe aesthetic with absolutely zero gradients.
  - 🥷 **Subtle Dark:** A stealthy, barely-there look with faint grey borders on pitch black.
  - 🔮 **Blurred Glass:** Stunning glassmorphism overlaying dynamic, looping YouTube video backgrounds (Fireplace, Cyberpunk, Lo-Fi, Rain, etc.).
- **Fluid & Responsive:** Built with fluid `clamp()` sizing and `vmax` units to perfectly scale and dominate the screen on any device—from small portrait phones (with auto-rotation logic) to massive 4K desktop monitors.
- **Gestures & Fullscreen:** 
  - **Single Tap / Click:** Instantly enter distraction-free fullscreen mode.
  - **Double Tap / Click:** Open the settings panel to customize your clock.
- **Extensive Customization:**
  - Toggle 12-hour (AM/PM) or 24-hour formats.
  - Show or hide the seconds counter.
  - Choose from multiple Date formats, or hide the date entirely.
  - Switch Timezones on the fly (Local, UTC, EST, GMT, JST, etc.).
  - Adjust glass blur intensity and background dimming.

## 🚀 Quick Start

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/itsadityakr/ChronoFlip.git
   cd ChronoFlip
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```
   Open your browser and navigate to `http://localhost:5173`.

### Building for Production
To build the application for production (e.g., to host on GitHub Pages):
```bash
npm run build
```
This generates a `dist/` folder containing your optimized, production-ready assets.

## 🛠️ Built With
- **React 18** - Frontend library
- **Vite** - Next Generation Frontend Tooling
- **Lucide React** - Beautiful SVG icons
- **CSS3** - Heavy use of modern CSS (`clamp()`, `vmax`, `backdrop-filter`, `perspective`, and 3D transforms) for fluid design and animations.

## 📝 Configuration (videos.json)
If you want to add or customize the YouTube background videos available in the "Blurred Glass" theme, simply edit the `src/videos.json` file to add your preferred YouTube Video IDs!
