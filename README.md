# 3D Product Showcase Website

A stunning, modern, premium-quality 3D product presentation website built with React, Vite, and react-three-fiber.

![3D Showcase](https://img.shields.io/badge/3D-Showcase-blue)
![React](https://img.shields.io/badge/React-18.3-61dafb)
![Three.js](https://img.shields.io/badge/Three.js-0.160-black)
![Vite](https://img.shields.io/badge/Vite-5.0-646cff)

## ✨ Features

- **Interactive 3D Viewer** - Built with react-three-fiber for smooth 3D model rendering
- **Auto Rotation** - Automatic model rotation with toggle controls
- **Exploded View** - Visualize internal components with animated exploded diagrams
- **Dynamic Lighting** - Professional lighting setup with shadows and reflections
- **Glassmorphism UI** - Modern glassmorphism design with blur effects
- **Framer Motion Animations** - Smooth, professional animations throughout
- **Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **Dark Mode** - Beautiful dark theme by default
- **Loading Progress** - Progress bar for model loading
- **Placeholder Mode** - Displays placeholder geometry when model.glb is missing

## 🚀 Quick Start

### Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

The website will open at `http://localhost:3000`

### Build

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

## 📁 Project Structure

```
PRINTHACK/
├── public/
│   └── model.glb          # Your 3D model (replace this file)
├── src/
│   ├── components/
│   │   ├── ModelViewer.jsx    # Main 3D viewer component
│   │   └── UI/
│   │       ├── Header.jsx     # Navigation header
│   │       ├── Hero.jsx       # Hero section with 3D viewer
│   │       ├── About.jsx      # About section
│   │       ├── Features.jsx   # Features grid
│   │       ├── Team.jsx       # Team members
│   │       └── Footer.jsx     # Footer with socials
│   ├── App.jsx            # Main app component
│   ├── main.jsx          # Entry point
│   ├── index.css         # Global styles
│   └── App.css           # App styles
├── index.html
├── vite.config.js
└── package.json
```

## 🎨 Customization

### Replace the 3D Model

Simply replace `/public/model.glb` with your own GLB file. The code will automatically load it.

```bash
# Copy your model to the public folder
cp /path/to/your/model.glb public/model.glb
```

### Update Content

- **Project Name**: Edit the logo text in `src/components/UI/Header.jsx`
- **Hero Title**: Modify text in `src/components/UI/Hero.jsx`
- **About Section**: Update content in `src/components/UI/About.jsx`
- **Features**: Edit the features array in `src/components/UI/Features.jsx`
- **Team Members**: Update the team array in `src/components/UI/Team.jsx`

### Customize Colors

Edit CSS variables in `src/index.css`:

```css
:root {
  --bg-primary: #000000;
  --accent-blue: #4a90e2;
  --accent-pink: #e24a90;
  --accent-green: #90e24a;
}
```

## 🎮 Controls

- **Auto Rotate**: Toggle automatic model rotation
- **Reset Camera**: Reset the camera to default position
- **Exploded View**: Animate model parts for exploded diagram view
- **Mouse Controls**: 
  - Left click + drag to rotate
  - Right click + drag to pan
  - Scroll to zoom

## 🛠️ Technologies

- **React 18.3** - UI library
- **Vite 5.0** - Build tool
- **Three.js 0.160** - 3D graphics library
- **@react-three/fiber** - React renderer for Three.js
- **@react-three/drei** - Useful helpers for react-three-fiber
- **Framer Motion** - Animation library
- **Inter Font** - Modern typography

## 📱 Responsive Design

The website is fully responsive and optimized for:
- Desktop (1920px+)
- Laptop (1024px - 1919px)
- Tablet (768px - 1023px)
- Mobile (320px - 767px)

## ⚡ Performance

- **60 FPS** rendering
- **Optimized lighting** with tone mapping
- **Lazy loading** for 3D models
- **Code splitting** with Vite
- **GPU acceleration** for 3D rendering

## 🎯 Use Cases

Perfect for:
- Product showcases
- Engineering projects
- Hackathon presentations
- Portfolio websites
- 3D model demonstrations
- CAD file presentations

## 📄 License

This project is open source and available for use in your projects.

## 🤝 Contributing

Feel free to fork, modify, and use this project for your needs!

## 💡 Tips

1. Use GLB format for 3D models (better compression than GLTF)
2. Optimize your 3D models before importing (reduce polygon count)
3. Keep model file size under 10MB for best performance
4. Use Blender or other 3D software to export to GLB format

## 📞 Support

For issues or questions, please create an issue in the repository.

---

**Built with ❤️ for PRINTHACK**
# printhack
