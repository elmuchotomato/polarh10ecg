# H10 ECG Analyzer

A single-page browser app for looking at ECG recordings from a Polar H10 chest
strap. It shows the ECG strip, an R-R tachogram, heart rate variability over
time and a beat log.

**Live site:** https://elmuchotomato.github.io/polarh10ecg/

## Layout

```
index.html    the whole app: markup, styles and signal processing
```

## Running

Use the live site, or serve this folder locally. There is no build step and
nothing to install.

- **Files:** open a recording exported from ECG Recorder or Polar Sensor Logger.
  The app finds the ECG column and sample rate itself, defaulting to 130 Hz.
- **Live:** connect to an H10 over Web Bluetooth, which needs Chrome on a computer
  or Android, or the Bluefy browser.
