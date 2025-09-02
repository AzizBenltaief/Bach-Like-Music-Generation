# 🎼 Bach-Like Music Generation with AI 🤖

This project is an AI-based music generation system that composes **Bach-style chorales** automatically using deep learning. 🎹✨

## 📖 Overview

The project uses a combination of **Convolutional Neural Networks (CNNs)** and **LSTM networks** to learn patterns in classical chorales and generate new music. Given a seed sequence of notes, the trained model predicts the next notes to create harmonized compositions in the style of Johann Sebastian Bach. 🎵

## ⚡ Features

- 🗂 Loads and preprocesses chorale datasets (CSV format).  
- 🔢 Converts notes and chords into sequences suitable for deep learning.  
- 🧠 Trains a CNN + LSTM model to learn harmonic and melodic patterns.  
- 🎶 Generates new chorales given a seed sequence.  
- 🎹 Outputs generated music as **MIDI files** for playback.  

## 🛠 Requirements

- Python 3.8+ 🐍  
- TensorFlow ⚡  
- NumPy 🔢  
- Pandas 🐼  
- music21 🎼  

Install dependencies via:

```bash
pip install tensorflow numpy pandas music21
