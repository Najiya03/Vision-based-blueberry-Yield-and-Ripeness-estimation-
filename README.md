# Blueberry Fruit Segmentation, Yield and Ripeness Estimation

This project presents an automated computer vision pipeline for blueberry fruit segmentation, yield estimation, and ripeness analysis.

The system uses a U-Net architecture with a ResNet50V2 encoder to accurately segment blueberry fruits from field images. Post-processing techniques such as Watershed Segmentation are applied to separate overlapping fruits and estimate fruit count. Ripeness is analyzed using HSV color-based classification.

---

## Features

- Blueberry fruit segmentation using U-Net
- ResNet50V2 encoder backbone
- Fruit counting using Watershed segmentation
- Ripeness estimation using HSV color analysis
- Yield estimation metrics
- Visualization of segmented fruits
- Interactive Gradio interface

---

## Tech Stack

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Gradio

---

## Dataset

- Agrivision Benchmark dataset: https://springernature.figshare.com/articles/dataset/AgriVision_A_Benchmark_Dataset_for_Advancing_Real-World_Robotic_Vision_in_Densely_Fruited_Blueberry_Crop/29222462

## Methodology

1. Image preprocessing
2. U-Net based segmentation
3. Binary mask generation
4. Watershed-based fruit separation
5. Fruit counting
6. Ripeness classification
7. Yield estimation

---

## Results

- Dice Score ≈ 0.79
- IoU Score ≈ 0.68
