# 🖐️ Hand Frame FX — Windows XP Edition

<p align="center">
  <strong>Real-time hand tracking that turns your webcam into a special-effects camera</strong>
</p>

<p align="center">
  <a href="https://amiralifirouzi.github.io/Hand-Frame-Fx/">🚀 Live</a>


---  

A creative computer vision web application that uses your webcam to track hand movements, allowing you to frame scenes and apply real-time visual effects. The entire user interface is a highly accurate, nostalgic recreation of Windows XP, complete with MS Paint, the Start menu, and the classic taskbar.

# 📝 What It Does
This application uses Google's MediaPipe Hands model to track hand landmarks in real-time. By raising both hands, the user creates a glowing, dynamic rectangular frame between their fingers. The video inside this hand-frame is processed with various visual effects, while the outside area is darkened and blurred.

To switch between effects, simply pinch your thumb and index finger together on either hand. You can also select effects, change frame colors using the classic MS Paint palette, and navigate the XP desktop environment.

# ✨ Features
1. Hand Tracking: Real-time 21-landmark tracking using MediaPipe (runs entirely on-device).
2. Gesture Control: Pinch to switch effects; frame the shot with your hands.
3. Visual Effects (FX):
- Cyberpunk: Crushed neon grade with scanlines and a city grid.
- Thermal: IR sensor simulation with an ironbow palette and hot-spot tracking.
- Heat Haze: Warping rays that bend harder near the floor.
- Chromatic: RGB split with occasional glitch slices.
- Echo: Light-painting motion trails.
- Pixelate: Low-res sensor mode with a visible pixel grid.
- Neon Edge: Edge detection blurred into a neon glow.
- Nostalgic UI: Fully interactive Windows XP environment (MS Paint window, draggable elements, Start menu, power-off screen).
# 🛠️ Tech Stack
- MediaPipe Hands (for on-device computer vision)
- HTML5 Canvas & JavaScript (for real-time pixel manipulation and effects)
- CSS3 (for the Windows XP Luna theme and desktop simulation)

## Author

**Amirali Firouzi**

Computer Vision • Mediapipe 

- GitHub: `@AmiraliFirouzi`
- LinkedIn: `www.linkedin.com/in/amirali-firouzi-2b714335a`

---

⭐ If you find this project useful, consider giving the repository a star.

