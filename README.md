# MonkeyPox-Detection
AI-based Detection of Monkeypox Virus Infection in Clinical Images

<h2>Overview</h2>
This repository contains the code and resources for an AI-based system developed by Santiago De La Garza, an Electrical and Computer Engineering student at The University of Texas at San Antonio. The system focuses on the automated detection of monkeypox virus infection in clinical images.

<h2>Abstract</h2>
Monkeypox is a rare but potentially fatal disease affecting humans and animals. Early detection is vital for effective treatment and disease control. This research project aims to develop an AI-based system for automated monkeypox detection in clinical images. The system uses deep learning algorithms to analyze images, identify characteristic features, and has the potential to improve diagnosis accuracy, especially in resource-limited settings.

<h2>Key Features</h2>
Convolution: Used for feature extraction from images.
Image Super-Resolution: Implemented using the Parallel Convolution Attention Network (PCAN).
Pooling: Utilized to consolidate features and reduce network complexity.
Batch Normalization: Applied to stabilize training and improve convergence.
Datasets: Details about the image dataset used for training and evaluation.
Algorithms: Explanation of the deep learning models employed.
Results: Evaluation of model performance.
Conclusion: Main findings and future improvements.
<h2>Methodology</h2>
<h3>Convolution</h3>
Convolution is a mathematical process used for feature extraction from images. In this project, it helps identify relevant patterns within monkeypox images.

<h3>Image Super-Resolution</h3>
Image super-resolution techniques, specifically PCAN, are employed to upscale low-resolution images. PCAN preserves important information and enhances image quality during the super-resolution process.

<h3>Pooling</h3>
Pooling layers are used to consolidate features learned by the network, reducing the model's complexity. Various pooling techniques are discussed.

<h3>Batch Normalization</h3>
Batch normalization is essential for stabilizing training and reducing convergence time in deep neural networks.

<h2>Datasets</h2>
Details about the dataset used, including image sources and labeling. Note that the dataset is not approved for real-world patient diagnostics.

<h2>Algorithms</h2>
Explanation of the deep learning models used, including VGG16 and YOLO V5, for image recognition and classification.

<h2>Results</h2>
Performance evaluation of the AI models, including accuracy on validation and testing sets. YOLO V5 outperformed VGG16 in accuracy.

<h2>Conclusion</h2>
Summary of findings, emphasizing the potential of AI in monkeypox detection. Future improvements, such as predicting infection severity and model selection, are discussed.
