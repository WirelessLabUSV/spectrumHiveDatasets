# spectrumHiveDatasets
Signal Datasets for AI-Based Spectrum Sensing applications

This dataset comprises 120,000 radio signal frames spanning 11 modulation classes and noise. The modulation classes included are: QPSK, DBPSK, GFSK, 16QAM, 64QAM, CSS LoRa SF7, CSS LoRa SF8, CSS LoRa SF9, CSS LoRa SF10, CSS LoRa SF11, and CSS LoRa SF12.

Each signal frame consists of 4,096 complex samples, captured at a sampling rate of 1 Msps, with a signal-to-noise ratio (SNR) ranging from -5 dB to 30 dB. The dataset incorporates Rician fading and clock offsets between -5 and +5 ppm, with each frame having normalized power.

The dataset is stored in MAT files, with each file containing two variables:
-IQ samples: Stored as a complex double array.
-Label: Provided in categorical format.

This dataset is well-suited for research and development in wireless signal processing, modulation classification, and deep learning applications.
