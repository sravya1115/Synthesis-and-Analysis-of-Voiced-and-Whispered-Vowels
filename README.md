# Voiced and Whispered Vowel Synthesis

This project uses MATLAB to create and analyze synthetic vowel sounds (like "a") in both **voiced** (normal speech) and **whispered** forms, for **male** and **female** voices.

## 📌 What This Project Does

- Creates vowel sounds using digital models.
- Compares male vs. female voices.
- Shows the difference between voiced and whispered speech.
- Uses both graphs and audio to analyze results.

## 🧪 How It Works

1. **Voiced Speech**  
   - Simulates vocal cord vibrations using impulse trains.
   - Applies glottal pulse models (Exponential, Rosenberg).
   - Uses LPC (Linear Predictive Coding) to model the vocal tract.
   - Adds lip radiation effects.

2. **Whispered Speech**  
   - Uses white noise (no vocal cord vibration).
   - Filters it using the same LPC model.

3. **Analysis**  
   - Frequency response plots.
   - Short-Time Fourier Transform (STFT).
   - Spectrograms.
   - Listening tests.

## 🎧 Audio Files

- `voiced_male.wav`
- `voiced_female.wav`
- `whispered_male.wav`
- `whispered_female.wav`

These files let you hear the differences.

## 📂 Files Included
- `report.pdf` – Full project report
