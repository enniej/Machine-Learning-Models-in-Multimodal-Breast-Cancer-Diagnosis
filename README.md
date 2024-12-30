# Impact of Advanced Feature Engineering on Machine Learning Models in Multimodal Breast Cancer Diagnosis
This project uses advanced feature engineering and multimodal data integration to enhance machine learning and deep learning models for breast cancer diagnosis. By leveraging  histopathological images and mammographic images, it develops robust methodologies to improve diagnostic accuracy, interpretability, and clinical relevance.

![image](https://github.com/user-attachments/assets/baf5892a-e1d5-4a9c-8137-56763779b581)

## **Summary**
Performance of Machine Learning Models
The study revealed a multifaceted landscape of model performance across different machine learning approaches. Traditional machine learning models, specifically Support Vector Machines (SVM) and Random Forests, demonstrated competitive performance, particularly when augmented with advanced feature engineering techniques. The SVM model showed substantial improvements with feature engineering, with increases of 7.17% in accuracy, 5.10% in F1 Score, and 7.43% in ROC AUC. While benefiting from feature engineering, the Random Forest model showed more modest improvements, suggesting its inherent capability to capture complex feature interactions.

In deep learning, the custom Convolutional Neural Network (CNN) and transfer learning models using ResNet50 and DenseNet121 architectures showcased the power of automatic feature learning. The DenseNet121 model consistently outperformed other architectures, achieving the highest overall performance with an ROC AUC of 0.9448 in the single modality setting. The Dual-Stream DenseNet121 model achieved the pinnacle of performance in the multimodal setting, with an accuracy of 0.9192 and an ROC AUC of 0.9699. This result underscores the potential of integrating multiple imaging modalities to enhance diagnostic accuracy.

### **Key Features**
- **Datasets**: Utilises BreakHis and CBIS-DDSM datasets for histopathological and mammographic imaging.
- **Advanced Techniques**: Implements texture analysis, shape descriptors, wavelet transformations, and multimodal integration.
- **Models**: Includes traditional machine learning models and advanced dual-stream deep learning architectures.

## **Access to Full Details**

For detailed explanations, refer to the `Breast Cancer prediction.pdf` in this repository, which outlines:
- Methodology
- Implementation
- Results and analysis


## References

The following references are some of were cited in the report and provide additional context:

1. **Ahmed et al., 2023**: "Fractal Dimension for Mammographic Image Analysis," *Journal of Medical Imaging*.
2. **Chen et al., 2024**: "Enhancing Robustness in Medical Imaging Models via Augmentation," *Proceedings of AI Healthcare*.
3. **Das et al., 2024**: "Challenges in Multimodal Medical Imaging Integration," *IEEE Transactions on Medical Imaging*.
4. **Devi et al., 2024**: "Performance of Deep Learning Models in Breast Cancer Diagnosis," *Computer Vision Applications in Medicine*.
5. **Feng et al., 2023**: "CBIS-DDSM Dataset: Insights and Applications," *Machine Learning in Radiology*.
6. **Huang et al., 2023**: "Histogram of Oriented Gradients in Histopathology," *Advances in Biomedical Engineering*.
7. **Mehta et al., 2023**: "BreakHis Dataset for Breast Cancer Research," *International Journal of Medical Imaging*.
8. **Nguyen et al., 2024**: "Combining Multimodal Data for Better Diagnostic Outcomes," *Healthcare AI Journal*.
9. **Okorie et al., 2024**: "Clinical Applications of Multimodal AI in Oncology," *Oncology AI Review*.
10. **Patel and Kashyap, 2023**: "Texture Entropy in Medical Imaging," *Signal Processing for Healthcare*.
11. **Wang et al., 2023**: "Improved Stratified Sampling for Imbalanced Medical Datasets," *Machine Learning in Medicine*.
12. **Xie et al., 2024**: "Feature Standardisation in Multimodal Imaging," *Journal of AI in Radiology*.
13. **Zhang et al., 2023**: "Handling Missing Data in Breast Cancer Datasets," *Medical Data Science Review*.
14. **Zouhri et al., 2024**: "Dimensionality Reduction in Multimodal Breast Cancer Diagnosis," *IEEE Biomedical Engineering Journal*.

## Important Notes

- **Datasets**: Due to size constraints, this repository does not include the BreakHis and CBIS-DDSM datasets. Instructions and links to these datasets are available in the report's reference section.
- **Code**: Scripts for preprocessing, feature engineering, training, and evaluation are provided in the `.pynb` file.

## **Conclusion**
This research has made significant strides in advancing machine learning-based breast cancer diagnosis by utilising multimodality and feature engineering to develop accurate, robust diagnostic tools. The study's holistic approach, which fuses multimodal imaging data with advanced feature engineering techniques, distinguishes it in the field and aligns with the pressing needs of modern healthcare systems like the NHS.
The results demonstrate that the best-performing algorithm has the potential to serve as an effective medical assistant for breast cancer diagnosis. This research not only reveals AI's potential to enhance diagnostic accuracy but also highlights important challenges in interpretability and clinical integration. Addressing these challenges is crucial for realising the full potential of AI-assisted breast cancer diagnosis and improving patient outcomes.

Ultimately, this study provides valuable insights into developing AI-based diagnostic tools that emphasise clinical real-world applicability. By balancing technological advancement with practical considerations, this research contributes to the ongoing effort to improve breast cancer diagnosis and, by extension, patient care in healthcare systems worldwide.

## Contact

For queries:
- GitHub: [enniej](https://github.com/enniej)

## License

### All Rights Reserved

This repository and its contents are © 2024 by Ene Ojaide. Redistribution, modification, or reuse in any form is strictly prohibited without explicit permission from the author.



