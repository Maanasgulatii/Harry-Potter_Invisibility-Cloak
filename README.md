# Harry-Potter_Invisibility-Cloak
This project uses **Python** and **OpenCV** to create an "invisibility cloak" effect, where any object placed in front of the camera becomes invisible. Inspired by the Harry Potter series, this effect works with any color of cloth, allowing it to blend seamlessly into the background.

### Features
- Real-time invisibility effect using OpenCV
- Captures a background frame to serve as the reference
- Detects any object in front of the background (regardless of color) and applies the cloak effect

### How It Works
- **Background Capture**: Captures the background with no objects in the frame.
- **Difference Masking**: Detects any new object by comparing each frame with the captured background.
- **Cloak Effect**: Replaces the object in the frame with the background, making it appear invisible.
