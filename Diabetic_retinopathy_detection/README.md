# Project : Diabetic Retinopathy detection

# Results

Mobilenet, VGGNet, and InceptionV2 are trained through transfer learning and achieved high accuracy.  See **Table 1**.

### Table 1: Information of models from transfer learning

| Model name   | Non-trainable parameters | Trainable parameters | Validation accuracy |
|-------------|-------------------------|----------------------|---------------------|
| Mobilenet   | 3,231,248               | 79,413               | 0.8547              |
| VGGNet      | 14,714,688              | 67,425               | 0.8803              |
| InceptionV2 | 54,339,312              | 1,679,289            | 0.8974              |

The evaluation results for each model are provided in **Table 2**.  
The ensemble evaluation results are shown in **Table 3**.

### Table 2: Evaluation results for three models

| Model Name  | Test Accuracy |
|------------|--------------|
| VGGNet     | 0.8350       |
| MobileNet  | 0.7864       |
| InceptionV2| 0.8350       |

### Table3: Evaluation result for ensemble learning

| Accuracy | Sensitivity (Recall) | Specificity | Precision | F1-Score | Confusion Matrix |
|----------|----------------------|-------------|-----------|-----------|-----------------|
| 0.8447   | 0.7969               | 0.9231      | 0.9444    | 0.8644    | TP=51, FP=3, TN=36, FN=13 |


The result of deep visualization is demonstrated in Figure 1.

<p align="center">
    <img src="diabetic_retinopathy/deep_visualization/grad_cam.png" alt="Grad-CAM visualization" style="display:block; margin:auto;" />
</p>

                                                Figure 1: Grad-CAM visualization of the model
