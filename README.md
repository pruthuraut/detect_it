# Teachable Machine Pose Model Integration

## Overview

This project integrates a Teachable Machine Pose Model into a web application using HTML and JavaScript. The web application captures webcam input, runs it through the PoseNet model provided by Teachable Machine, and displays the detected poses along with classification predictions.

## Prerequisites

- Modern web browser with webcam support
- Internet connection for loading external scripts and models

## Getting Started

1. Clone or download this repository to your local machine.
2. Open the `index.html` file in a web browser.

## Usage

1. Click the "Start" button to initiate the webcam and pose detection.
2. The application will display the detected poses along with classification predictions on the right side of the canvas.

## Project Structure

- `index.html`: HTML file containing the structure of the web page.
- `style.css`: CSS file for styling the web page. (embeded)
- `script.js`: JavaScript file for handling webcam input, pose detection, and classification. (embeded)
- `ml.jpg`: Background image for the web page.

## Dependencies

- TensorFlow.js (`https://cdn.jsdelivr.net/npm/@tensorflow/tfjs@1.3.1/dist/tf.min.js`)
- Teachable Machine Pose Model (`https://cdn.jsdelivr.net/npm/@teachablemachine/pose@0.8/dist/teachablemachine-pose.min.js`)
