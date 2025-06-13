# spectrumHiveDatasets 
Signal Datasets for AI-Based Spectrum Sensing applications

Link for download : https://1drv.ms/u/c/fdd6e836b8b400f4/ET4Tt-aNJxRAgwp_KnPEaEgBIQ1_PUaZQ2edvQm9Tf22Sg?e=YIboz2

If you use this dataset please cite:
1. Mutescu, P. M., Popa, V., & Lavric, A. (2025). LoRa Communications Spectrum Sensing Based on Artificial Intelligence: IoT Sensing. Sensors (Basel, Switzerland), 25(9), 2748. https://doi.org/10.3390/s25092748
2. P. -M. Mutescu, A. Lavric, A. -I. Petrariu, A. -M. Cailean and V. Popa, "Radio Spectrum Sensing Framework for Large-Scale, High-Density IoT Sensor Networks," in IEEE Access, vol. 13, pp. 64594-64609, 2025, doi: 10.1109/ACCESS.2025.3558746.

This dataset comprises 120,000 radio signal frames spanning 11 modulation classes and noise. The modulation classes included are: QPSK, DBPSK, GFSK, 16QAM, 64QAM, CSS LoRa SF7, CSS LoRa SF8, CSS LoRa SF9, CSS LoRa SF10, CSS LoRa SF11, and CSS LoRa SF12.

Each signal frame consists of 4,096 complex samples, captured at a sampling rate of 1 Msps, with a signal-to-noise ratio (SNR) ranging from -5 dB to 30 dB. The dataset incorporates Rician fading and clock offsets between -5 and +5 ppm, with each frame having normalized power.

The dataset is stored in MAT files, with each file containing two variables:

-IQ samples: Stored as a complex double array.

-Label: Provided in categorical format.

This dataset is well-suited for research and development in wireless signal processing, modulation classification, and deep learning applications.

ACKNOWLEDGMENT: This dataset was developed as a result of project number PN-IV-P2-2.1-TE-2023-1476, within PNCDI IV, grant of the Ministry of Research, Innovation and Digitization, CNCS-UEFISCDI.
