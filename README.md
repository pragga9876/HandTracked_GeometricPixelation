# Hand-Tracked Geometric Pixelation

A beginner TouchDesigner project that combines real-time hand tracking with geometric shapes and a pixelation effect.

Inspired by Instagram reels set to the song *“I Hope You Find Some Peace of Mind”*. Most of those reels were created with traditional video editing. This version explores a similar calm, abstract aesthetic using live hand tracking and generative geometry instead.

![Project Screenshot](screenshot.png)

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

HandTracked_GeometricPixelation/
├── Hand_Tracking.2.toe          ← your main project file
├── screenshot.png               ← preview image
├── toxes/                       ← from the MediaPipe release
│   ├── MediaPipe.tox
│   └── (other helper toxes)
└── README.md


---

## How to set up

1. Download this repository (Code → Download ZIP) and unzip it.

2. Download the MediaPipe plugin:
   - Go to https://github.com/torinmb/mediapipe-touchdesigner/releases
   - Download the latest `release.zip`
   - Unzip it

3. Copy the entire `toxes` folder from the MediaPipe release and place it **next to** the `.toe` file.

4. Open `Hand_Tracking.2.toe` in TouchDesigner.

5. If the MediaPipe component shows a missing external tox warning:
   - Select the MediaPipe component
   - Go to the **Common** parameter page
   - Enable **External .tox**
   - Point the path to `toxes/MediaPipe.tox` (relative path preferred)

6. Allow webcam access when prompted.

The project should now run with live hand tracking and the geometric + pixelation effects.

---

## Controls & Notes

- Hand landmarks appear as red dots connected by green lines
- A large geometric shape (triangle/polygon) is overlaid on the video
- Pixelation intensity can be adjusted via the `pixelate` component (Horizontal & Vertical Pixel Size)
- This is a beginner-level project created while learning TouchDesigner and following hand-tracking tutorials

---

## Credits & Inspiration

- **MediaPipe TouchDesigner Plugin** by Torin Blankensmith  
  https://github.com/torinmb/mediapipe-touchdesigner
- Visual inspiration from Instagram reels set to *“I Hope You Find Some Peace of Mind”*
- Built as a learning project exploring real-time hand tracking + geometric abstraction

---

## License

Free for learning, personal use, and non-commercial projects.  
Please credit the MediaPipe plugin if you share derivatives.