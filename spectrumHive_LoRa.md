Signal Datasets for AI-Based LoRa modulation SF detection

Link for download : 

If you use this dataset please cite:

1. P. M. Mutescu, A. Lavric, A. I. Petrariu, and V. Popa, “Deep Learning Enhanced Spectrum Sensing for LoRa Spreading Factor Detection,” 2023 13th International Symposium on Advanced Topics in Electrical Engineering (ATEE), pp. 1–5, Mar. 2023, doi: 10.1109/ATEE58038.2023.10108224.

2. P. M. Mutescu, A. Lavric, A. I. Petrariu, and V. Popa, “A Hybrid Deep Learning Spectrum Sensing Architecture for IoT Technologies Classification,” 2023 17th International Conference on Engineering of Modern Electric Systems, EMES 2023, 2023, doi: 10.1109/EMES58375.2023.10171667.
This dataset comprises 156,000 radio signal frames using the CSS LoRa modulation with spreading factors from 7 to 12, with 26,000 signal frames for each LoRa SF.

The LoRa signals are synthetically generated using Bassel Al Homssi library under Matlab environment [1]. Each signal frame consists of 4,096 complex samples, captured at a sampling rate of 1 Msps, with a signal-to-noise ratio (SNR) ranging from -20 dB to 30 dB with an increment of 2 dB. The dataset incorporates Rician fading and clock offsets between -5 and +5 ppm, with each frame having normalized power.
The dataset is stored in MAT files, with each file containing two variables:

-IQ samples: Stored as a complex double array.

-Label: Provided in categorical format.

This dataset was used to train and evaluate a CNN for LoRa SF detection, which obtained a live inference detection accuracy of 99.16% using SX1276 LoRa transceivers. 

ACKNOWLEDGMENT: This dataset was developed as a result of project number PN-IV-P2-2.1-TE-2023-1476, within PNCDI IV, grant of the Ministry of Research, Innovation and Digitization, CNCS-UEFISCDI.

[1] - B. Al Homssi, K. Dakic, S. Maselli, H. Wolf, S. Kandeepan, and A. Al-Hourani, "IoT Network Design using Open-Source LoRa Coverage Emulator," in IEEE Access. 2021.
