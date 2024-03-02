# Spectral Analysis of Music Tracks

This program performs a spectral analysis of two songs, "Será Que No Me Amas" by Luis Miguel and "Blame It On the Boogie" by The Jacksons, aiming to objectively compare their audio components. The analysis focuses on a specific time frame (from 3 to 6 seconds) and utilizes the Fourier Transform to examine frequency magnitudes.

## Dependencies
- `numpy`
- `scipy`
- `matplotlib`

## Usage
```python
python spectral_analysis.py
```

## Methodology
To investigate similarities between two allegedly similar songs, we consulted plagiarism accusation lists. Eventually, we chose to analyze the spectral features of "Blame It on the Boogie" by The Jacksons and "Será que no me amas" by Luis Miguel.

## Results Analysis
The obtained graphs reveal significant insights into the similarities and differences between the analyzed songs. This figure exclusively represents the sound components, excluding vocals. The results suggest a notable similarity in spectral characteristics, supporting the hypothesis of plagiarism.

The presence of peaks may indicate the existence of specific instruments or frequencies that are similar in both compositions. This suggests the use of similar instruments or the reproduction of specific melodic patterns, possibly indicating similarity in notes or chords

## Conclusions
Initial graph comparisons showed substantial differences, attributed to varying amplitudes. To address this, audio normalization and noise reduction filtering were applied, focusing on frequency magnitudes. Similarities between the seconds 3 and 6 of both songs were highlighted, possibly due to the absence of vocals during that period. Further improvement could involve analyzing voiceless, acoustic-style songs.

While the Fourier Transform-based spectral analysis reveals significant resemblance, it is insufficient to determine musical plagiarism conclusively. A comprehensive analysis considering various musical composition aspects would be required for a more accurate assessment of potential plagiarism.
