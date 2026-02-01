# 🏊 Freestyle Swim Technique Analyzer Pro

AI-powered swimming technique analysis using computer vision and pose estimation.

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-1.28+-red.svg)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0.10+-green.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

## Features

- **Real-time Pose Analysis**: Uses MediaPipe Pose for accurate body landmark detection
- **Technique Metrics**: Analyzes torso lean, forearm angle, body roll, and kick mechanics
- **Breathing Detection**: Tracks breathing patterns and bilateral balance
- **Stroke Phase Recognition**: Identifies Entry, Pull, Push, and Recovery phases
- **Visual Comparison**: Side-by-side overlay comparing swimmer to ideal form
- **Comprehensive Reports**: PDF reports, CSV data exports, and annotated video output

## Demo

Upload a freestyle swimming video and get instant analysis:

| Metric | Description |
|--------|-------------|
| Technique Score | Overall score (0-100) based on form |
| Stroke Rate | Strokes per minute |
| Body Roll | Shoulder rotation angle |
| Kick Symmetry | Left/right leg balance |
| Kick Depth | Amplitude of kick motion 
