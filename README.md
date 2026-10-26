# 🦇 DC: SnyderVerse | A Cinematic CSS Slider

> A cinematic DC-inspired image slider built with HTML and CSS, featuring Superman, Batman, The Flash, and Darkseid through timed animations and dramatic visual effects.

---

## 🖤 About The Project

**DC: SnyderVerse** is a front-end practice project inspired by the darker visual atmosphere of the DC universe.

The project features four iconic characters, each appearing in a cinematic frame before sliding away to make room for the next one.

- 🦸 Superman
- 🦇 Batman
- ⚡ The Flash
- 👹 Darkseid

Built entirely with **HTML5 and CSS3**, the project explores CSS animations, image-filled typography, layered gradients, and visual composition without using JavaScript.

---

## 🌐 Live Demo

🦇 [**View the Live Website**](https://manibagherinezhad-ops.github.io/DC-SnyderVerse/)

*Replace the placeholder with your actual GitHub Pages URL.*

---

## 🎬 

- 🦸 **Four Iconic Characters**  
  A rotating showcase featuring Superman, Batman, The Flash, and Darkseid.

- 🎞️ **CSS-Powered Slideshow**  
  Four independent `@keyframes` animations control the movement and timing of each slide.

- 🖼️ **Image-Filled Typography**  
  Character names use `background-clip: text` to display image textures inside the letters.

- 🌑 **Cinematic Background**  
  Dark colors, blue and burgundy radial gradients, and bottom overlays create a dramatic atmosphere.

- 📐 **Layered Layout**  
  Absolute positioning and `overflow: hidden` keep the animated slides inside the main frame.

- 🔁 **Infinite Animation Loop**  
  The slideshow repeats continuously without requiring user interaction.

- ⚡ **No JavaScript**  
  All animation and visual effects are handled with CSS.

---

## 🛠️ Built With

- 🌐 HTML5
- 🎨 CSS3
- 🎞️ CSS Animations
- 🗝️ CSS `@keyframes`
- 🖼️ Background Images
- 🌈 Radial & Linear Gradients
- ✍️ `background-clip: text`
- 📐 CSS Positioning & Flexbox

---

## 📂 Project Structure

```text
DC-SnyderVerse/
│
├── index.html
│
└── img1/
    ├── download.jpg
    ├── 57430892b9b3180e37fb1d1cc951716b.jpg
    ├── The Flash Wallpaper 4K Ultra HD pc.jpg
    └── all-hail-darkseid-4k-iu.jpg
```

*Note: The HTML and CSS are contained in a single `index.html` file, while the `img1/` folder stores the character images.*

---

## 🎥 How It Works

The project uses a fixed **800 × 500 pixel** container as the stage for the slideshow.

Each `figure` occupies the entire frame and uses absolute positioning to move horizontally. The `overflow: hidden` property hides slides outside the container.

```css
.panjareh {
    width: 800px;
    height: 500px;
    position: relative;
    overflow: hidden;
    border-radius: 10px;
}
```

Each character has a separate animation sequence that controls when it enters, stays visible, and exits the frame.

### 🗝️ CSS Animations & Keyframes

The project defines four animation sequences:

- `aks1` for Superman
- `aks2` for Batman
- `aks3` for The Flash
- `aks4` for Darkseid

The keyframes use percentage-based timing to coordinate the slides within a repeating 20-second animation cycle.

### 🖼️ Image-Filled Text

The character captions use `background-clip: text` and transparent text color to reveal an image inside the letters.

```css
background-clip: text;
color: transparent;
```

Each caption has its own background image and positioning, connecting the typography to the character's visual identity.

### 🌑 Background & Overlays

Radial gradients introduce subtle blue and burgundy lighting against a near-black background. A `::after` pseudo-element adds a bottom gradient to each image, creating a darker, more cinematic composition.

---

## 🎯 Purpose

This project was created as a front-end practice exercise to improve skills in:

- HTML structure and CSS layout
- CSS animations and `@keyframes`
- Absolute positioning and layering
- Gradient backgrounds and pseudo-elements
- Image cropping and image-filled typography
- Visual storytelling through motion

The goal was to explore how a simple webpage can create an engaging visual experience using only HTML and CSS.

---

## 🎨 Design Direction

Inspired by the darker aesthetic of the **DC SnyderVerse**, the design combines a near-black background, cool blue lighting, burgundy accents, and bold uppercase captions.

Each character gets a moment in the spotlight, while the coordinated animations keep the presentation moving. Instead of a conventional website layout, the browser becomes a small cinematic display.

---

## 👨‍💻 Author

### Mani Bagherinezhad

**Front-End Developer**

- 🐙 [GitHub](https://github.com/manibagherinezhad-ops)
- 💼 [LinkedIn](https://linkedin.com/in/mani-bagherinezhad-641217350/?isSelfProfile=true)
- 📸 [Instagram](https://instagram.com/manibagherinezhad_dev/)

---

## 🧑‍🏫 Mentor

### Parsa Ghorbanian

**Mentor**

- 🐙 [GitHub](https://github.com/parsaGhorbanian)
- 📸 [Instagram](https://instagram.com/parsa_ghorbanian_web/)
- 🌐 [Website Design Training](https://trainingsitedesign.ir/learn-web-design/)

---

## ⚠️ Disclaimer

This is an unofficial, fan-made project created for educational and portfolio purposes.

DC Comics, its characters, and associated artwork belong to their respective copyright holders. This project is not affiliated with or endorsed by DC Comics, Warner Bros., or Zack Snyder.

---

### 🦇 Four legends. One frame. A universe in motion.

**Made with HTML, CSS & a little cinematic ambition.**
