# Parking Space Detection

## Description

This Python project provides a solution for real-time parking space detection and analysis using computer vision techniques. The system processes images or video feeds to determine the availability of parking spaces in a given area.

## Features

- **Real-time Detection**: Detects and marks parking spaces in real-time based on the provided input (images, videos, or camera feed).
- **Interactive Initialization**: Allows users to interactively mark parking spaces on a reference image for initialization.
- **Visual Feedback**: Provides visual feedback on the number of free parking spaces available.

## Usage

### Mark Parking Spaces

1. Run the `ParkingSpacePicker.py` script to mark parking spaces on a reference image:

    ```bash
    python ParkingSpacePicker.py
    ```

   - Left-click to mark a parking space.
   - Right-click to remove a marked parking space.
   - Close the window to save the marked positions.

### Analyze Parking Spaces

2. Run the `main.py` script to analyze parking space availability in a video feed:

    ```bash
    python main.py
    ```

   - The script will process the video feed and display the parking spaces in real-time, indicating the availability of each space.

## Prerequisites

- Python 3.x
- OpenCV
- numpy
- cvzone

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your_username/your_repository.git
    ```

2. Navigate to the project directory:

    ```bash
    cd your_repository
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Customization

You can customize the parameters in the scripts (`main.py`, `ParkingSpacePicker.py`) according to your requirements.


## A taste of the project 🚗🚙

![parking](https://github.com/Margalit-Abermad/Parking-spaces-available/assets/100418442/448f9c8d-2685-4c42-b8c9-72de3623c13c)

