# 🌸 Flower Bloom — Hand Gesture Control

> Grow a beautiful animated flower using nothing but your hands.

An interactive computer vision project that transforms your webcam into a magical garden. Using **MediaPipe Hands**, the application tracks hand gestures in real time, allowing users to bloom flowers, grow stems, and create wind through natural hand movements.

---a

## ✨ Demo

<p align="center">
  <img src="https://media.giphy.com/media/l0HlBO7eyXzSZkJri/giphy.gif" width="700" alt="Demo Placeholder">
</p>

> Replace the GIF above with your own screen recording.

---

# 🎬 Animation Preview

### 🌺 Flower Bloom Animation

```text
      🌸
    🌸🌸🌸
  🌸🌸🌸🌸🌸
      │
      │
      │
```

The flower smoothly opens and closes based on your **left-hand pinch**.

---

### 🌱 Growth Animation

```text
    🌸
     │
     │
     │
     │
     │
```

The stem continuously grows or shrinks using your **right-hand pinch**.

---

### 🌬 Wind Animation

```text
      🌸
     /
    /
   /
```

Move your hands sideways to generate wind and make the flower naturally sway.

---

# 🎮 Gesture Controls

| Gesture | Animation |
|----------|-----------|
| 🤏 Left Hand Pinch | 🌸 Flower Blooms |
| 🤏 Right Hand Pinch | 🌱 Flower Grows |
| 👋 Move Hands Sideways | 🌬 Wind Sways Flower |

---

# ✨ Features

🌸 Real-time Hand Tracking

Detects both hands simultaneously using **MediaPipe Hands**.

---

🌺 Bloom Animation

The flower petals smoothly interpolate between closed and fully opened states.

---

🌱 Growth Animation

Pinch with your right hand to grow the flower stem naturally.

---

🌬 Dynamic Wind

Hand movement controls the wind intensity, producing realistic swaying motion.

---

🎥 Live Webcam

Mirrored webcam provides intuitive interaction.

---

🎨 Procedural Drawing

The flower is rendered entirely on an HTML Canvas.

No images.

No SVG.

Everything is drawn mathematically every frame.

---

🖐 Hand Skeleton Overlay

Visual feedback while MediaPipe tracks your fingers.

---

✨ Smooth Motion

Gesture values are filtered to eliminate jitter for fluid animations.

---

🌙 Beautiful UI

- Glassmorphism instruction panel
- Animated loading screen
- Soft vignette
- Responsive full-screen experience

---

# 🏗 Project Structure

```
Flower-Bloom/
│
├── index.html
├── style.css
├── app.js
└── README.md
```

---

# 🚀 Getting Started

## 1. Clone Repository

```bash
git clone https://github.com/yourusername/flower-bloom.git
```

---

## 2. Open Project

```bash
cd flower-bloom
```

---

## 3. Run Local Server

Python

```bash
python -m http.server 8080
```

or

Node

```bash
npx serve .
```

---

## 4. Open Browser

```
http://localhost:8080
```

Allow camera permission and enjoy.

---

# 🌼 How It Works

## Step 1

MediaPipe detects 21 landmarks for each hand.

```
Thumb Tip
Index Tip
Middle Tip
Ring Tip
Pinky Tip
```

---

## Step 2

The application calculates the distance between

```
Thumb Tip
↓

Index Tip
```

This distance determines the pinch amount.

---

## Step 3

Pinch distance is mapped into animation values.

```
Small Distance
↓

Flower Opens
```

```
Large Distance
↓

Flower Closes
```

---

## Step 4

Hand velocity generates procedural wind.

```
Move Hand →

Wind Force ↑

Flower Sways 🌸
```

---

# 🎨 Animation Pipeline

```text
Camera
   │
   ▼
MediaPipe Hands
   │
   ▼
Finger Landmarks
   │
   ▼
Gesture Detection
   │
   ▼
Animation Variables
   │
   ▼
Canvas Rendering
   │
   ▼
Animated Flower 🌸
```

---

# 📦 Dependencies

Loaded directly from CDN.

- MediaPipe Hands
- MediaPipe Camera Utils

No build tools required.

---

# 🌍 Browser Support

✅ Chrome

✅ Edge

✅ Brave

⚠ Firefox

⚠ Safari

---

# 💡 Customization

You can easily modify

- 🌺 Petal colors
- 🌸 Number of petals
- 🌱 Growth speed
- 🌬 Wind sensitivity
- ✨ Bloom smoothness
- 🎨 Background
- 🌈 Gradients
- 🖐 Hand skeleton visibility

---

# 🔒 Privacy

- Camera is processed locally inside the browser.
- No video is uploaded.
- No images are stored.
- No user data is collected.

---

# 🛠 Built With

- HTML5
- CSS3
- JavaScript
- Canvas API
- MediaPipe Hands

---

# ⭐ Future Improvements

- 🌼 Multiple flowers
- 🌈 Dynamic color palettes
- 🦋 Butterflies
- 🌧 Rain effect
- 🌞 Day/Night cycle
- 🎵 Background music
- 🌺 Garden mode
- 🌻 Different flower species
- 📱 Mobile gesture optimization

---

# ❤️ Credits

Hand Tracking powered by **Google MediaPipe**.

Built with HTML, CSS and JavaScript.

---

# 📄 License

MIT License

Feel free to use, modify and share this project.

---

<p align="center">

## 🌸 Left Pinch → Bloom  
## 🌱 Right Pinch → Grow  
## 🌬 Move Hands → Wind

**Made with ❤️ using MediaPipe + Canvas**

⭐ If you enjoyed this project, consider giving it a star!

</p>
