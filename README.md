# Parking Space Monitoring System

## Overview
The Parking Space Monitoring System is a real-time application designed to monitor parking lots, detect, and count available parking spots using a video feed. It tracks the positions of predefined parking spaces and highlights them as either free or occupied using advanced image processing techniques.

## Features
- Real-time video feed processing.
- Detection and tracking of parking spaces.
- Identification of free and occupied parking spots.
- Dynamic highlighting of parking statuses in the video feed.

## Technologies Used
- **Programming Language**: Python
- **Image Processing Library**: OpenCV

## How It Works
1. **Video Feed Analysis**:
   - Processes the video feed frame-by-frame.
   - Identifies parking spaces based on predefined coordinates.
2. **Image Processing Techniques**:
   - **Thresholding**: Differentiates between vehicles and the parking lot background.
   - **Blurring**: Reduces noise for smoother detection.
   - **Dilation**: Enhances features to detect occupied spaces accurately.
3. **Spot Classification**:
   - Determines the status (free/occupied) of each parking space.
   - Updates and displays the real-time status overlayed on the video feed.

## Installation
### Prerequisites
- Python 3.6 or later
- OpenCV library

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/parking-monitoring-system.git
