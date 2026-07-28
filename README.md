# Hand-Tracked Geometric Pixelation

A beginner TouchDesigner project that combines real-time hand tracking with geometric shapes and a pixelation effect.

Inspired by Instagram reels set to the song *“I Hope You Find Some Peace of Mind”*. Most of those reels were created with traditional video editing. This version explores a similar calm, abstract aesthetic using live hand tracking and generative geometry instead.

![Project Screenshot](screenshot.png)
<img width="1438" height="802" alt="image" src="https://github.com/user-attachments/assets/aee4d0da-c72b-44fd-bcca-a0983bf61948" />


---

## What it does

- Uses **MediaPipe** hand tracking to detect both hands in real time (landmarks shown as red points + green skeleton)
- Overlays large geometric shapes (triangular / polygonal forms) that interact with the tracked hands
- Applies a customizable **pixelation** effect across the video
- Runs entirely in real time from a webcam

The visual result is a soft, fragmented, geometric look that responds to hand movement.

---

## Demo

[Paste your YouTube demo video link here]

---

## Requirements

- **TouchDesigner** 2025.32820 (or compatible recent version)
- **MediaPipe TouchDesigner Plugin** by Torin Blankensmith  
  Recommended version: the latest release (or the one you originally used)  
  Download: https://github.com/torinmb/mediapipe-touchdesigner/releases

---

## Project Structure (after setup)
