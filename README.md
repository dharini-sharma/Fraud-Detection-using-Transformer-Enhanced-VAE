# Fraud Detection with Transformer-Enhanced VAE

## Project Overview

This project implements an innovative approach to financial fraud detection by combining **Transformer architectures** with **Variational Autoencoders (VAE)** for enhanced anomaly detection in transaction data.

## Key Innovation

**Individual Transaction Processing**: Unlike traditional sequence-based approaches, this method uses transformers to enhance features within individual transactions, creating richer representations for the VAE to learn from.

## Results Achieved

| Model | Dataset | ROC AUC | Improvement |
|-------|---------|---------|-------------|
| Baseline VAE | PaySim | 0.5989 | - |
| **Transformer + VAE** | PaySim | **0.7921** | **+32.3%** |

## Technologies Used

- **Deep Learning**: PyTorch, Transformer Networks, Variational Autoencoders
- **Data Processing**: Pandas, NumPy, Scikit-learn
- **Evaluation**: ROC AUC, Precision, Recall, Confusion Matrix Analysis

## Files

- `PaySim_Model.ipynb` - Complete implementation with results

## Methodology

1. **Baseline VAE**: Traditional anomaly detection using reconstruction error
2. **Individual Transaction Transformer**: Feature enhancement using self-attention
3. **Enhanced VAE**: Improved anomaly detection on transformer embeddings
4. **Comprehensive Evaluation**: ROC AUC, precision, recall analysis

## Key Findings

- **32.3% improvement** in ROC AUC over baseline VAE approach
- **Individual transaction processing** proves more effective than sequence-based methods
- **Clear error separation**: 14x difference between normal and fraud reconstruction errors
- **Robust performance** on extremely imbalanced data (0.17% fraud rate)

## Development Status

**Current Phase**: Proof of Concept Complete ✅  
**Next Phase**: Real-world Dataset Validation (IEEE) 🔄  
**Future**: Research Publication and Advanced Ensemble Methods 📊

*This repository demonstrates core concepts and achieved results. Full methodology and advanced implementations are under active development for potential academic publication.*

## Research & IP Notice

This work represents ongoing research in transformer-enhanced fraud detection. The demonstrated approach shows **novel applications of individual transaction processing** with significant performance improvements (32% ROC AUC improvement).

**For Academic Collaboration or Research Inquiries**: dharinisharma.la@gmail.com
**Citation**: If you use concepts from this work, please reference this repository and contact for proper attribution.

*Core algorithmic innovations are being prepared for academic publication.*
