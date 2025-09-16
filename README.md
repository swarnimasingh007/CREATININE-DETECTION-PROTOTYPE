# Computer Vision–Based Colorimetric Biosensor Prototype

**Short:** Raspberry Pi + OpenCV prototype for colorimetric creatinine detection (Jaffé reaction) — imaging, analysis, calibration & display.

## Features
- Camera-based capture & analysis (reflectance/transmission).
- Pseudo-absorbance computation (green-channel, 520 nm proxy).
- LFA strip and tube modes; test/control peak detection.
- Full-screen result display for point-of-care use.
- Calibration script + CSV logging.

## Hardware
- Raspberry Pi (3/4 recommended)
- USB 1080p camera or Pi Camera
- 3.5" TFT display (optional)
- White LED(s) and 520 nm green LED(s)
- Diffuser, matte white background, strip/tube jig
- Optional: small breadboard + resistors + GPIO wiring

See `docs/hardware.md` for wiring, jig diagrams and component suggestions.

## Quick start (on Raspberry Pi)
1. Clone repo:
```bash
git clone https://github.com/<your_username>/computer-vision-colorimetric-biosensor.git
cd computer-vision-colorimetric-biosensor
