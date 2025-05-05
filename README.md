# 🖐️ Hand-Tracking-Project

A real-time hand tracking project using OpenCV and MediaPipe that efficiently detects and visualizes hand landmarks through your webcam feed.  
Great for gesture recognition, interactive interfaces, and experimentation!

## ✨ Features

- 👐 Detects up to two hands simultaneously in live video.
- 🎯 Draws clear hand landmarks and connections on each frame.
- 📍 Returns the position of each landmark for further use, like gesture recognition.
- 🖨️ Prints landmark coordinates to the console.
- ⚡ Displays real-time FPS overlay for performance insight.

## 🛠️ Requirements

- Python 3.6+
- OpenCV (`cv2`)
- MediaPipe

Install dependencies:# Hand-Tracking-Project
## 🚀 Getting Started

1. **Clone this repository:**
    ```bash
    git clone https://github.com/your-username/Hand-Tracking-Project.git
    cd Hand-Tracking-Project
    ```
2. **Run the main hand tracking module:**
    ```bash
    python HTModule.py
    ```
3. **Quit:**  
   Focus the image window and press `q` to exit.

## 📂 Files Included

- **HTModule.py:** Main, modular hand tracker with landmark detection and visualization.
- **HandTracking.py:** Simple, single-script version for experiments and quick demos.

## 📝 How It Works

1. 📷 Captures frames from your camera.
2. 🤚 Detects & tracks hands with MediaPipe.
3. 🖊️ Draws landmarks and hand connections on video.
4. 💻 Prints coordinates of hand landmarks to console.
5. ⏱️ Overlays FPS metric for real-time feedback.

## ⚙️ Customization

- Adjust number of hands, confidence thresholds, or visualization options in the `handDetector` class.
- Use printed landmark lists to build your own gesture controls or hand-based interfaces!

## 📄 License

Open-source under the MIT License.

## 🔗 References

- [Google MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html)
- [OpenCV Docs](https://docs.opencv.org/)

---

🙋‍♂️ Issues or ideas? Open an issue or a pull request – contributions welcome!