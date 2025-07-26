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

## 🛠️ Technologies Used

- **Deep Learning**: PyTorch, Transformer Networks, Variational Autoencoders
- **Data Processing**: Pandas, NumPy, Scikit-learn
- **Evaluation**: ROC AUC, Precision, Recall, Confusion Matrix Analysis

## Files

- `PaySim_Fraud_Detection_Transformer_VAE.ipynb` - Complete implementation with results
- `requirements.txt` - Required Python packages

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

## Academic & Professional Impact

This work demonstrates **novel individual transaction processing** with transformers, showing significant performance improvements over traditional VAE approaches. The methodology is suitable for both **practical deployment** and **research publication**.
