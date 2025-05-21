Advanced Spectrum Sensing for 5G and Beyond using SSNet
The rapid evolution toward fifth-generation (5G) wireless networks and beyond has significantly increased the demand for efficient spectrum management and utilization. Traditional spectrum sensing techniques often fall short in accurately identifying spectrum occupancy, particularly in environments where multiple heterogeneous radio signals coexist within the same frequency band.

To overcome these limitations, we propose a novel deep learning-based spectrum sensing approach that leverages the Short-Time Fourier Transform (STFT) in combination with neural networks to effectively learn and recognize spectrogram patterns.

Proposed Method: SSNet
We introduce SSNet, a semantic segmentation network built upon an encoder-decoder architecture, specifically designed to:

Precisely detect multiple coexisting signals within the spectrum

Segment time-frequency representations (spectrograms) to identify spectral content based on both time and frequency occupancy

Key Features
Attention Mechanism: Focuses on relevant spectral regions to improve detection accuracy

Multi-scale Feature Extraction: Captures both fine-grained and abstract spectral patterns

Robust Signal Segmentation: Effectively distinguishes overlapping signals and handles complex signal structures

Experimental Results
Comprehensive simulations demonstrate the robustness and effectiveness of SSNet under a variety of challenging channel conditions and RF impairments. The model achieves high accuracy in identifying:

5G New Radio (NR)

LTE (Long Term Evolution)

even in spectrally congested environments.

Key Contributions
A novel application of semantic segmentation for advanced spectrum sensing

A robust and lightweight architecture capable of real-time deployment in dynamic and noisy radio environments

Superior performance compared to conventional sensing methods, particularly in dense spectrum sharing scenarios

<div align="center"> <img src="https://github.com/user-attachments/assets/86328592-6a94-4325-bbea-abbab0a45ca4" alt="SSNet Spectrogram Segmentation 1" width="500"/> <br/> <img src="https://github.com/user-attachments/assets/e5a1f412-359c-4474-8bd2-7c061ed2a80d" alt="SSNet Spectrogram Segmentation 2" width="500"/> <br/> <img src="https://github.com/user-attachments/assets/f8cac0b7-4efb-4c95-a575-94d382280635" alt="SSNet Architecture and Results" width="500"/> </div>
