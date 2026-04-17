
PyTorch CNN implementation for MNIST digit classification.

## Files
- `MNIST_CNN_Classifier.ipynb` - Main notebook with training and evaluation

## Quick Start
1. Open in [Google Colab](https://colab.research.google.com/drive/1v_j7wG5uQM3QsPcVuwc-vm6CdbAegv7I?usp=sharing)
   - **Note:** Make a copy (File → Save a copy in Drive) before running
2. Run all cells

## Results
- Test Accuracy: ~99%
- Model weights saved in `saved_models/`

```
/content/saved_models
├── accuracy_plot.png           # Training vs validation accuracy curves
├── loss_plot.png               # Training vs validation loss curves
├── classification_report.txt   # Class-wise precision, recall, F1-score
├── best_model.pth              # Checkpoint for resuming training
├── final_model_weights.pth     # Trained weights for inference/prediction
├── full_model.pth              # Complete model object
└── mnist_cnn_complete.pth      # Weights with metadata
```

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/f7f4e742-e05d-440e-8416-b35d34367639" />
