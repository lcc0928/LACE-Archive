# LACE-Archive

**Lung Adenocarcinoma CT Classification — EfficientNetV2 Model Weights & 5-Fold CV Results**

---

## English

This repository archives the trained model weights, 5-fold cross-validation splits, and evaluation curves for lung adenocarcinoma classification on the Chest CT-Scan dataset using EfficientNetV2 (input size: 224×224).

### Contents

| Directory | Description |
|-----------|-------------|
| `weights/` | Trained checkpoints (7 files) |
| `splits/` | 5-fold train/val image lists (10 `.txt` files) |
| `figures/` | Training and validation curves (5 figures) |

### Model Checkpoints

| File | Description |
|------|-------------|
| `best_model.pth` | Best model overall |
| `best_model_fold1.pth` ~ `best_model_fold5.pth` | Per-fold best models |
| `efficientnetv2_ct.pth` | Auxiliary checkpoint |

### Data Splits

All 5-fold split files are provided as plain text lists of image filenames, preserving the exact partition used in training.

### Evaluation Figures

- `training_loss_curve.png` — Training loss across epochs
- `validation_accuracy_curve.png` — Validation accuracy across epochs
- `validation_auc_curve.png` — Validation AUC across epochs
- `validation_sensitivity_curve.png` — Validation sensitivity across epochs
- `validation_specificity_curve.png` — Validation specificity across epochs

### License

This repository is for research and reference purposes only.

---

## 中文

本仓库归档了使用 EfficientNetV2（输入尺寸 224×224）在 Chest CT-Scan 数据集上进行肺腺癌分类训练的模型权重、5 折交叉验证划分及评估曲线。

### 内容

| 目录 | 说明 |
|------|------|
| `weights/` | 训练好的模型检查点（共7个文件） |
| `splits/` | 5折交叉验证划分文件（10个 `.txt` 文件） |
| `figures/` | 训练与验证曲线图（5张） |

### 模型检查点

| 文件 | 说明 |
|------|------|
| `best_model.pth` | 全局最佳模型 |
| `best_model_fold1.pth` ~ `best_model_fold5.pth` | 各折最佳模型 |
| `efficientnetv2_ct.pth` | 辅助检查点 |

### 数据划分

提供全部 5 折划分文件（纯文本格式的图像文件名列表），保留训练时使用的精确数据划分。

### 评估图表

- `training_loss_curve.png` — 训练损失曲线
- `validation_accuracy_curve.png` — 验证准确率曲线
- `validation_auc_curve.png` — 验证AUC曲线
- `validation_sensitivity_curve.png` — 验证敏感性曲线
- `validation_specificity_curve.png` — 验证特异性曲线

### 许可

本仓库仅供研究和参考用途。
