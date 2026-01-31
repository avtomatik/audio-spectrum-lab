# Audio Spectrum Lab

A personal mini-project exploring the intersection of **music**, **mathematics**, and **signal processing**.

The goal of this project is to record sounds, analyze their properties (spectrum, frequency content, loudness, etc.), and gradually evolve from laptop-based prototyping to an **autonomous Arduino-based audio system** using a MAX9814 microphone module.

---

## Motivation

I am passionate about both **music and mathematics**, and this project serves as a hands-on playground to:

- Experiment with audio signal processing
- Apply mathematical tools such as the Fourier Transform
- Learn practical audio analysis using Python
- Bridge software prototyping with embedded hardware

---

## Project Roadmap

### Phase 1 – Laptop Prototyping (Python)
- Record audio using laptop or USB microphone
- Visualize waveforms and spectra
- Perform FFT-based frequency analysis
- Plot spectrograms and time–frequency representations

### Phase 2 – Embedded Audio (Arduino)
- Capture audio using MAX9814 microphone
- Stream audio or features to a PC via serial
- Perform basic real-time processing on Arduino
- Move toward autonomous operation

---

## Technologies

### Software
- Python
- NumPy
- SciPy
- Matplotlib
- Librosa
- PyAudio / SoundDevice
- PySerial

### Hardware
- Laptop / PC
- Arduino (Uno / Nano / similar)
- MAX9814 electret microphone amplifier
- Breadboard, jumper wires

---

## Repository Structure (planned)

```

audio-spectrum-lab/
│
├── python/
│   ├── record_audio.py
│   ├── fft_analysis.py
│   ├── spectrogram.py
│
├── arduino/
│   ├── max9814_basic_read.ino
│
├── docs/
│   └── notes.md
│
└── README.md

```

---

## Status

🚧 Work in progress  
Currently setting up audio acquisition and spectral analysis in Python.

---

## Future Ideas

- Real-time spectrum visualization
- Pitch detection and harmonic analysis
- Sound-triggered hardware responses (LEDs, motors)
- Comparing laptop mic vs MAX9814 signal quality

---

## License

This project is for learning and experimentation.  
[LICENSE](LICENSE.md).
