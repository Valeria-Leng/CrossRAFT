# CrossRAFT: Cross-Domain Complex-Valued Feature Extraction for Ultrasound Motion Estimation

This repository contains the official implementation of **CrossRAFT**, an end‑to‑end trainable network for sub‑sample motion estimation directly from complex‑valued ultrasound signals (analytic or IQ data). The method is built upon the RAFT architecture and uses complex‑valued feature encoders with a custom correlation module to preserve phase information, enabling accurate 2D displacement estimation.

📄 **Paper**: [Will be linked after publication]

## 🔧 Features
- Direct processing of complex‑valued analytic or IQ signals
- Complex‑valued neural network (CVNN) layers for phase‑aware feature extraction
- Custom correlation module bridging complex input and real output spaces
- Hybrid training: supervised pre‑training + bidirectional unsupervised fine‑tuning
- Evaluation on simulated phantom, synthetic cardiac, and *in vivo* echocardiographic data

## ⏳ Availability
**All code will be made publicly available upon paper acceptance.**  
We are currently finalizing the release package, including training scripts, pretrained models, and evaluation pipelines.

## 🚀 Planned Contents
- Training and inference scripts for CrossRAFT (IQ and analytic versions)
- Data preprocessing tools for RF, IQ, and analytic signal generation
- Pretrained weights on simulated phantom and synthetic cardiac datasets

## 📬 Contact
For any questions or collaborations, please open an issue or contact the corresponding author.

## 📜 License
This project will be released under the [MIT License](LICENSE) after publication.

---

*Stay tuned – we are working hard to make CrossRAFT useful for the ultrasound imaging community.*
