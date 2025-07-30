# Deep Learning for Early-Stage Oral Cancer Prognosis and Classification
This repository presents a deep learning-based ensemble model that combines EfficientNetB3 and ResNet50 to detect Oral Squamous Cell Carcinoma (OSCC) from medical images. By using transfer learning, selective layer freezing, and dropout regularization, the model achieves superior accuracy and generalization — outperforming individual base models.

📌 Introduction: 
Oral cancer remains a significant global health concern, with many cases detected only at later stages, reducing patient survival rates. Early detection is crucial. This project proposes a deep learning solution using an ensemble of two powerful architectures to automate the detection of OSCC in oral lesion images.

🏗️ Model Architecture:
The proposed ensemble model integrates:

EfficientNetB3: A scalable and lightweight convolutional neural network optimized for performance and efficiency.

ResNet50: A residual network that enables training of deeper models without vanishing gradient issues.

✅ Why Ensemble?
Combining these models enhances:

Generalization on unseen data

Robustness to image variations

Performance beyond individual networks

🗂️ Dataset:
Total images: 5,192

Labels: Normal, OSCC

Split:

Training: 3,634 images

Validation: 779 images

Testing: 779 images

📥 Source: Kaggle - OSCC Dataset (link to be inserted)

⚙️ Training & Evaluation:
Techniques Used:
Transfer Learning: Initialized with pre-trained weights (ImageNet)

Selective Layer Freezing: Retains foundational features while fine-tuning top layers

Dropout: Reduces overfitting and improves model robustness


✅ The ensemble model shows remarkable performance and generalization, making it the best-performing architecture in this study.

🧾 Conclusion:
The ensemble model integrating EfficientNetB3 + ResNet50 offers a reliable and accurate solution for early OSCC detection. By significantly reducing overfitting and improving accuracy, it has the potential to aid healthcare professionals in clinical settings.

🔮 Future Scope:
📈 Data Expansion: Incorporate larger and multimodal datasets (histopathological images, clinical metadata).

🧠 Explainable AI (XAI): Enhance interpretability of predictions for clinical trust.

🏥 Deployment: Develop real-time clinical applications using mobile/web interfaces.

🔐 Federated Learning: Train models in privacy-preserving distributed environments.

🤝 Contributions:
Have suggestions or improvements?
Feel free to fork this repo, make changes, and submit a pull request. Contributions are welcome!

🙏 Acknowledgments:
Dataset: Kaggle

Domain Knowledge Support: Healthcare professionals and medical research articles

Pre-trained Models: ImageNet weights from Keras Applications

📬 Contact:
For collaborations, feedback, or queries, feel free to reach out.
Let’s use AI to drive impactful healthcare innovations. 💡

