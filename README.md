# Rice Leaf Diseases Object Detection based on YOLOv8 Algorithm
## Overview
This repository contains the implementation of a high-performance object detection system designed to identify and classify rice leaf diseases. Utilizing the YOLOv8 architecture, this project focuses on robust localization and classification of diseased areas in rice leaves, with a specific comparative analysis between "background" and "non-background" datasets.
The system leverages advanced deep learning techniques, including transfer learning and image augmentation, to enhance model generalization and prevent overfitting. Furthermore, it incorporates Stratified K-Fold Cross-Validation to ensure balanced class distribution across the training data.
## Key Features
- Model Architecture: Implementation of the YOLOv8 object detection model, optimized for efficiency and accuracy.
- Data Handling: Effective application of image augmentation and Stratified K-Fold Cross-Validation to maintain data integrity and improve model robustness.
- Edge Computing Optimization: The model is validated for deployment on edge computing devices, demonstrating significant performance and faster inference times compared to standard laptop environments.
- Performance Metrics: Achieved high accuracy and localization performance, with superior results observed in non-background image conditions.
## Performance Summary
Based on the experimental results, the YOLOv8 model demonstrated significant efficacy:Model Performance: 
- High localization and classification accuracy, with metrics reaching up to 95.3% and 94.1% for non-background data, respectively.
- Edge Inference: Simulation on edge computing hardware yielded inference times ranging from 39 to 45 ms.
- Generalization: The use of transfer learning and frozen initial layers allowed the model to effectively retain foundational features while adapting to specific disease identification tasks.

## Deployment Note
The research indicates that while model quantization for edge device deployment may result in a minor reduction in evaluation metrics (approximately 5-10%), the system remains highly effective for real-time agricultural monitoring applications.

## Future Research Directions
To further advance this study, the following developments are proposed:
- Scalability: Expansion of the detection system to include a wider variety of rice diseases and the integration of video-based processing.
- Architectural Optimization: Refinement of the detection model architecture to improve the localization of small-scale objects while maintaining, or enhancing, computational speed.

## References
- Badan Pusat Statistik. (2023, October 16). Luas panen dan produksi padi di Indonesia, 2023 (Angka Sementara). Badan Pusat Statistik.
- Fikri, A. (2022). Rice Leaf 5 Diseases. Kaggle. https://www.kaggle.com/Datasets/adefiqri12/riceleafsv3
- Ibadurrohman, U. S., Kurniawan, E., Az-Zukhruf, A., Pratiwi, E. B., Adinanta, H., & Yunianto, M. (2024, November). Comparative Analysis of Deep Learning Models for Accurate Detection of Rice Leaf Diseases. In 2024 IEEE International Conference on Smart Mechatronics (ICSMech) (pp. 123-128). IEEE.
- Trinh, D. C., Mac, A. T., Dang, K. G., Nguyen, H. T., Nguyen, H. T., & Bui, T. D. (2024). Alpha-EIOU-YOLOv8: An Improved Algorithm for Rice Leaf
Disease Detection. AgriEngineering, 6(1), 302–317. https://doi.org/10.3390/agriengineering6010018 

## Explanation of Code

