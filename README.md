# Color Recognition Application

A Python-based Color Recognition Application that allows users to double-click on any visible color in an image, detects the selected pixel’s RGB values, matches them with the closest color name from a CSV dataset, and displays the recognized color information in real time using OpenCV.

## Overview

This project was developed as an Artificial Intelligence group project. It is designed to help users identify colors from images quickly and accurately through a simple interactive interface.

The application is useful for tasks in:
- Graphic design
- Web development
- Image analysis
- Color-based visual inspection

## Features

- Double-click on any pixel in the image
- Detects RGB values of the selected pixel
- Matches the closest color name from a CSV dataset
- Displays the color name and RGB values in real time
- Dynamic text color adjustment for better readability
- Easy exit using the `Esc` key

## Technologies Used

- Python
- OpenCV
- pandas
- NumPy
- Matplotlib (optional / extended version)

## Project Files

- `color_recognition.py` – Main application
- `ai_final_project.py` – Extended version with plotting
- `colors.csv` – Color dataset
- `color_image.jpg` – Sample input image
- `docs/` – Proposal and final report files

## How It Works

1. The application loads an image.
2. The user double-clicks on any visible color.
3. The selected pixel's RGB values are extracted.
4. The application compares those RGB values with entries in `colors.csv`.
5. The closest matching color name is displayed on the image along with RGB values.

## Requirements

Install the required dependencies:

```bash
pip install -r requirements.txt
