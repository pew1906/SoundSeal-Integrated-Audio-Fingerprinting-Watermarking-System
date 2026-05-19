# Integrated Audio Fingerprinting and Watermarking using PERTH and AUDIFY

## Overview

This project presents an integrated system for **audio fingerprinting** and **digital watermarking** using **PERTH** and **AUDF** techniques. The main objective is to provide secure audio authentication, copyright protection, and content identification through robust signal processing methods.

The system combines:

* **Audio Fingerprinting** – to uniquely identify audio content based on extracted features.
* **Digital Watermarking** – to embed hidden ownership or authentication data inside audio signals.
* **PERTH Algorithm** – used for secure and efficient watermark embedding.
* **AUDIFY Framework** – used for audio feature extraction and fingerprint generation.

This integrated approach improves media security, prevents unauthorized distribution, and enables reliable audio tracking.

---

# Features

* Secure audio watermark embedding and extraction
* Robust audio fingerprint generation
* Audio ownership verification
* Tamper detection and authentication
* Noise-resistant fingerprint matching
* Supports WAV audio processing
* Visualization of waveform and spectrogram
* Efficient signal processing pipeline

---

# Technologies Used

* **Python 3.x**
* NumPy
* SciPy
* Librosa
* Matplotlib
* SoundFile / PyDub
* Signal Processing Techniques

---

# System Architecture

```text
Input Audio
     |
     v
Feature Extraction (AUDF)
     |
     v
Fingerprint Generation
     |
     v
Watermark Embedding (PERTH)
     |
     v
Watermarked Audio Output
     |
     v
Verification & Extraction
```


# Installation

## Clone the Repository

```bash
git clone https://github.com/your-username/Integrated-Audio-Fingerprinting-Watermarking.git
cd Integrated-Audio-Fingerprinting-Watermarking
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Usage

## Run the Main Program

```bash
python src/main.py
```

## Generate Audio Fingerprint

```bash
python src/fingerprint.py
```

## Embed Watermark

```bash
python src/watermark.py
```

## Verify Audio Authenticity

```bash
python src/verification.py
```

---

# Working Principle

## 1. Audio Preprocessing

The input audio signal is normalized and converted into a suitable format for analysis.

## 2. Fingerprint Generation (AUDF)

The AUDF module extracts unique audio features such as:

* Spectral peaks
* Frequency components
* Temporal patterns
* Acoustic descriptors

These features are converted into compact fingerprints used for matching and identification.

## 3. Watermark Embedding (PERTH)

The PERTH algorithm embeds hidden information into the audio signal while maintaining audio quality.

Properties:

* Imperceptibility
* Robustness
* Security
* Resistance to compression and noise

## 4. Verification

The system extracts the watermark and compares generated fingerprints with stored fingerprints to verify authenticity.

---

# Applications

* Copyright protection
* Music identification systems
* Audio authentication
* Broadcast monitoring
* Piracy detection
* Secure media distribution
* Forensic audio analysis

---

# Advantages

* High security and reliability
* Fast audio matching
* Robust against signal distortion
* Efficient watermark recovery
* Scalable for large audio databases

---

# Future Enhancements

* Real-time audio monitoring
* Deep learning-based fingerprint extraction
* Multi-format audio support
* Cloud-based fingerprint database
* Mobile application integration

---

# Sample Output

```text
Fingerprint Generated Successfully
Watermark Embedded Successfully
Verification Result: Authentic Audio
```

---

# Requirements

```text
Python >= 3.8
NumPy
SciPy
Librosa
Matplotlib
PyDub
SoundFile
```

---

# Research Objectives

* To integrate watermarking and fingerprinting into a single framework
* To improve audio security and ownership protection
* To achieve robust and accurate audio identification
* To reduce tampering and unauthorized duplication

---

# Conclusion

This project demonstrates a secure and efficient framework for integrating audio fingerprinting and watermarking using PERTH and AUDF methods. The system provides reliable audio authentication and copyright protection while preserving audio quality.

---

# Contributors

* Prachi Kumar

---

