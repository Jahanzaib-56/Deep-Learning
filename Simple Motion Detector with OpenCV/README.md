# Simple Motion Detector

A lightweight motion detection script using OpenCV that monitors a live webcam feed, highlights moving objects with bounding boxes, and saves snapshots when motion is detected.

---

## Demo

| No Motion | Motion Detected |
|-----------|-----------------|
| Green frame counter visible | Red "Motion Detected!!" text + green bounding boxes |

---

## How It Works

The script maintains a rolling buffer of recent grayscale frames. On each iteration it computes the absolute difference between the oldest and newest frame in the buffer. Regions with significant pixel change are treated as motion, filtered for noise, and highlighted with bounding boxes.

---

## Features

- Live webcam feed with real-time motion highlighting
- Noise filtering — ignores small/irrelevant movements
- Auto-saves snapshots on motion detection (with cooldown to avoid flooding)
- Frame counter overlay
- Press `Esc` to exit cleanly

---

## Requirements

- Python 3.x
- OpenCV

Install dependencies:
```bash
pip install opencv-python
```

---

## Usage

```bash
python motion_detector.py
```

> **Note:** Run from a terminal directly. Running via the VS Code run button may cause unexpected interruptions with camera streams.

---

## Configuration

You can tweak these variables at the top of the script:

| Variable | Default | Description |
|----------|---------|-------------|
| `gap` | `5` | Number of frames to compare across |
| `cooldown` | `2` | Seconds between saved snapshots |
| Contour area threshold | `500` | Minimum pixel area to count as motion |

---

## Project Structure

```
simple-motion-detector/
│
├── motion_detector.py      # Main script
├── README.md
└── Motion_frame_*.jpg      # Saved snapshots (generated at runtime)
```

---

## Built With

- [OpenCV](https://opencv.org/) — Computer vision and image processing

---

## License

This project is open source and available under the [MIT License](LICENSE).
