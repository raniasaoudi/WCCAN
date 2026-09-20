# WCCAN

WCCAN: Windowed Cross-Contrast Attention Network for Multi-Contrast Brain Magnetic Resonance Image Super-Resolution

Official repository for the paper:

**WCCAN: Windowed Cross-Contrast Attention Network for Multi-Contrast Brain Magnetic Resonance Image Super-Resolution**

Published in *Magnetic Resonance in Medical Sciences (MRMS)*, Volume 25, Issue 4, 2026.

## Status

The repository is currently being updated.

## Authors and Corresponding Author

**Authors:** Rania Saoudi, Djamel Eddine Boudechiche, Zoubeida Messali, and Samir Brahim Belhaouari

**Corresponding author:** Rania Saoudi

**Email:** [rania.saoudi@univ-bba.dz](mailto:rania.saoudi@univ-bba.dz)

## Abstract

**Purpose:** Most existing multi-contrast MRI super-resolution (MCMSR) methods rely on spatial-domain fusion and global attention, overlooking explicit high-frequency (HF) priors while incurring high computational costs. This work addresses these limitations through a general reference-guided MCMSR framework designed for low computational cost, applicable to any contrast pairing rather than a fixed clinical protocol.

**Methods:** We introduce a wavelet-guided HF prior modeling block for directional-based decomposition and bounded nonlinear enhancement, enabling precise extraction and controlled amplification of anatomical details from both reference and target contrasts. We further introduce a triple cross-contrast fusion module, based on a windowed cross-contrast attention module, to efficiently transfer high-frequency information between contrasts and reduce computational complexity compared to global attention schemes. Additionally, to reduce feature differences across contrasts, a consistent feature fusion module with selective spatial adaptive modulation is incorporated.

**Results:** Extensive experiments on IXI and M4Raw datasets demonstrate that our proposed windowed cross-contrast attention network (WCCAN) framework consistently outperforms state-of-the-art single- and multi-contrast MRI SR methods in terms of quantitative accuracy and visual fidelity. In addition, the WCCAN model achieves lower computational complexity and faster inference time compared to the other MCMSR methods.

**Conclusion:** The proposed WCCAN framework provides an efficient and accurate solution for MCMSR, demonstrating superior reconstruction quality with reduced computational cost compared to existing methods.

## WCCAN Architecture

<p align="center">
  <img src="https://github.com/user-attachments/assets/7f609a3e-11b5-4766-9674-afa0488796e0" width="592" alt="WCCAN architecture">
</p>

## Data and Pretrained Weights

The preprocessed data and pretrained model weights used in this study are available upon reasonable request for research purposes.Researchers who wish to access the data or pretrained weights are invited to contact the **corresponding author**.

## Acknowledgment

We sincerely thank the authors of **DCAMSR** for making their PyTorch implementation available. Their implementation served as the basis for the development of our WCCAN framework.

## Citation

If you use WCCAN in your research, please cite:

```bibtex id="wccan_citation"
@article{saoudi2026wccan,
  title   = {WCCAN: Windowed Cross-Contrast Attention Network for Multi-Contrast Brain Magnetic Resonance Image Super-Resolution},
  author  = {Saoudi, Rania and Boudechiche, Djamel Eddine and Messali, Zoubeida and Belhaouari, Samir Brahim},
  journal = {Magnetic Resonance in Medical Sciences},
  volume  = {25},
  number  = {4},
  year    = {2026},
  doi     = {10.2463/mrms.mp.2026-0092}
}
```

## Publication

The official journal article is available through *Magnetic Resonance in Medical Sciences (J-STAGE)*.

**DOI:** [10.2463/mrms.mp.2026-0092](https://doi.org/10.2463/mrms.mp.2026-0092)
