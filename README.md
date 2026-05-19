# 🎵 Integrated Audio Fingerprinting and Watermarking using PERTH & AUDIFY

> A secure and intelligent framework for **audio authentication**, **copyright protection**, and **content identification** using advanced signal processing techniques.

---

## 📌 Overview

This project presents an integrated system that combines **Audio Fingerprinting** and **Digital Watermarking** using the **PERTH** algorithm and **AUDIFY** framework.

The primary goal is to provide:

* 🔐 Secure audio authentication
* 🛡️ Copyright protection
* 🎧 Reliable audio identification
* 🚫 Protection against unauthorized duplication and tampering

The system extracts unique audio fingerprints and embeds invisible watermark data into audio files while preserving audio quality.

---

## ✨ Key Features

✅ Secure watermark embedding & extraction
✅ Robust audio fingerprint generation
✅ Audio ownership verification
✅ Tamper detection mechanism
✅ Noise-resistant fingerprint matching
✅ WAV audio file support
✅ Waveform & spectrogram visualization
✅ Efficient signal processing pipeline
✅ Lightweight and scalable architecture

---

## 🧠 Core Technologies

| Technology            | Purpose                   |
| --------------------- | ------------------------- |
| **Python 3.x**        | Main programming language |
| **NumPy**             | Numerical computations    |
| **SciPy**             | Signal processing         |
| **Librosa**           | Audio analysis            |
| **Matplotlib**        | Data visualization        |
| **PyDub / SoundFile** | Audio handling            |

---

# 🏗️ System Architecture

```text
          ┌─────────────────┐
          │   Input Audio   │
          └────────┬────────┘
                   │
                   ▼
      ┌─────────────────────────┐
      │ Feature Extraction      │
      │       (AUDIFY)          │
      └────────┬────────────────┘
               │
               ▼
      ┌─────────────────────────┐
      │ Fingerprint Generation  │
      └────────┬────────────────┘
               │
               ▼
      ┌─────────────────────────┐
      │ Watermark Embedding     │
      │        (PERTH)          │
      └────────┬────────────────┘
               │
               ▼
      ┌─────────────────────────┐
      │ Watermarked Audio Output│
      └────────┬────────────────┘
               │
               ▼
      ┌─────────────────────────┐
      │ Verification & Recovery │
      └─────────────────────────┘
```

---

# 📂 Project Structure

```text
Integrated-Audio-Fingerprinting-Watermarking/
│
├── dataset/                  # Input audio files
├── output/                   # Watermarked audio outputs
├── fingerprints/             # Generated fingerprints
├── watermark/                # Watermark data
│
├── src/
│   ├── preprocessing.py      # Audio preprocessing
│   ├── fingerprint.py        # Fingerprint generation
│   ├── watermark.py          # Watermark embedding/extraction
│   ├── verification.py       # Audio verification
│   └── main.py               # Main execution file
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

# ⚙️ Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/Integrated-Audio-Fingerprinting-Watermarking.git
cd Integrated-Audio-Fingerprinting-Watermarking
```

---

## 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Usage

## Run Complete System

```bash
python src/main.py
```

---

## Generate Audio Fingerprint

```bash
python src/fingerprint.py
```

---

## Embed Watermark

```bash
python src/watermark.py
```

---

## Verify Audio Authenticity

```bash
python src/verification.py
```

---

# 🔍 Working Principle

## 🎚️ 1. Audio Preprocessing

The input audio signal is:

* Normalized
* Filtered
* Converted into analyzable format

This ensures consistent and accurate processing.

---

## 🎵 2. Fingerprint Generation (AUDIFY)

The AUDIFY module extracts unique audio features such as:

* Spectral peaks
* Frequency components
* Temporal patterns
* Acoustic descriptors

These features are converted into compact fingerprints for matching and identification.

---

## 🔐 3. Watermark Embedding (PERTH)

The PERTH algorithm embeds hidden information inside the audio signal while maintaining high audio quality.

### Key Properties

* Imperceptibility
* Robustness
* Security
* Resistance to compression & noise

---

## ✅ 4. Verification

The system:

* Extracts the hidden watermark
* Generates fingerprints
* Compares with stored fingerprints

to verify authenticity and detect tampering.

---

# 🌍 Applications

🎧 Music Identification Systems
📡 Broadcast Monitoring
🛡️ Copyright Protection
🔍 Forensic Audio Analysis
📁 Secure Media Distribution
🚫 Piracy Detection
🔐 Audio Authentication Systems

---

# 🚀 Advantages

✔️ High security and reliability
✔️ Fast fingerprint matching
✔️ Robust against distortion and noise
✔️ Efficient watermark recovery
✔️ Scalable for large audio databases

---

# 🔮 Future Enhancements

* 🤖 Deep learning-based fingerprint extraction
* ☁️ Cloud-based fingerprint database
* 📱 Mobile application integration
* 🎙️ Real-time audio monitoring
* 🎵 Multi-format audio support

---

# 📊 Sample Output

```text
[INFO] Fingerprint Generated Successfully
[INFO] Watermark Embedded Successfully
[INFO] Verification Result: Authentic Audio
```

---

# 📋 Requirements

```text
Python >= 3.8
NumPy
SciPy
Librosa
Matplotlib
PyDub
SoundFile
```

Install dependencies using:

```bash
pip install -r requirements.txt
```

---

# 🎯 Research Objectives

* Integrate watermarking and fingerprinting into a unified framework
* Improve audio ownership protection
* Enable robust and accurate audio identification
* Prevent tampering and unauthorized duplication

---

# 📈 Future Scope

This project can be extended into:

* AI-powered copyright monitoring systems
* Streaming platform authentication
* Blockchain-based audio ownership verification
* Enterprise media protection systems

---

# 👩‍💻 Contributor

### Prachi Kumar

AI & Data Science Undergraduate
Passionate about Machine Learning, Signal Processing & Intelligent Systems

---

# 📜 License

This project is licensed under the **MIT License**.

---

# ⭐ Support

If you found this project useful:

🌟 Star the repository
🍴 Fork the project
📢 Share it with others

---

# 🔗 GitHub Repository

Replace with your actual repository link:

```text
https://github.com/your-username/Integrated-Audio-Fingerprinting-Watermarking
```
