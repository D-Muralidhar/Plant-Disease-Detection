# 🌿 Plant Disease Detection
This project uses deep learning (MobileNetV2 with transfer learning) to detect diseases in plant leaves from images, focusing on tomato, potato, and pepper crops. 

Key features:
- Trained on a curated subset of the PlantVillage dataset (Kaggle).
- Uses transfer learning: MobileNetV2 base (frozen) + custom classifier head.
- Preprocessing: 224×224 images, 80/10/10 train/val/test split.
- Evaluation: Classification report and confusion matrix show strong per-class performance.

The trained model (plantmodel.keras) can be deployed for real-time disease monitoring in agriculture.
# How to run
Open Jupyter Notebook using cmd or Use Google Colab
Run the .ipynb file

# Results Summary
The model achieves 93.5% test accuracy in classifying healthy vs. diseased leaves, enabling early diagnosis and better crop management.
