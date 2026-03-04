# Project_TCEs

## Drone Detection
### Concept

This project aims to detect drones using machine learning. The main principle is sound-based detection. It begins by collecting audio samples of drone flight sounds and non-drone sounds, then converting them into spectrogram graphs for analysis. The system then compares the sound patterns between drone flight and non-flight conditions.

## project structure
<pre>
Project_TCEs/
├─README.md
├─audio_file/
│   ├─Drone_high5m_25m.wav(example)
│   └─Naturalsound.wav(example)
├─data_cleaning/
│   └─Plot_spectrogram.ipynb
├─dataset/
│   ├─train/
│   │   ├─drone/
│   │   └─non-drone/ 
│   └─val/
│   │   ├─drone/
│   │   └─non-drone/
└─src/ 
    └─main
    
</pre>