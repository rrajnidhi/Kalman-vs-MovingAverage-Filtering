Below is a **short, crisp, copy-paste-ready README.md** rewritten to emphasize **comparison between Kalman filtering and Window Averaging** as you requested, including the YouTube thumbnail.

---

# Comparison of Kalman Filtering and Window Averaging for Temperature Sensor Data

This Arduino project compares two filtering methods, Kalman filtering and moving window averaging, to clean noisy temperature sensor readings. The goal is to evaluate which method provides smoother and more stable output for real-time temperature measurements.

---

## Overview

* Raw voltage is read from an analog temperature sensor on pin A0
* A Kalman filter is applied to estimate a cleaner, noise-reduced signal
* A 50-sample moving window average is used as a second filtering method
* All three values (raw, Kalman filtered, window averaged) are printed for direct comparison

This allows side-by-side evaluation of responsiveness, stability and noise reduction for both filtering methods.

---

## Demonstration Video

Click the thumbnail below to watch the comparison.

[![Watch the video](https://img.youtube.com/vi/HRmuSDLJ-RA/0.jpg)](https://youtu.be/HRmuSDLJ-RA)

---

## How to Use

1. Upload the code to an Arduino board.
2. Connect your temperature sensor to analog pin A0.
3. Open the serial monitor at 9600 baud.
4. Observe raw, Kalman filtered and window averaged outputs for comparison.

