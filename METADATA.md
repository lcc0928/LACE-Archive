# Training Metadata

## Model
- Backbone: EfficientNetV2
- Input Size: 224 × 224
- Framework: PyTorch

## Dataset
- Name: Chest CT-Scan images dataset
- Classes: 4 (Adenocarcinoma, Large Cell, Squamous Cell, Normal)

## Training
- Cross-Validation: 5-fold
- Checkpoints: Best model + per-fold models

## Evaluation Metrics
- Accuracy, AUC, Sensitivity, Specificity
- Curves available in `figures/`