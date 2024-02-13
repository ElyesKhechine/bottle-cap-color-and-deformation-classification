# Bottle Cap Color and Deformation Classification

### Project conducted by Elyes Khechine, Racem Ghorbel, and team members

**Technologies:** Python, NumPy, OpenCV, scikit-learn, scikit-image, Keras, pandas, joblib, Matplotlib Pyplot, SGDClassifier

## Introduction

This project focuses on the classification of bottle cap colors and deformation types using machine learning techniques. By leveraging a combination of Python libraries and custom algorithms, our goal is to automate quality control processes in recycling facilities.

## Project Scope

Conducted between December 8, 2022, and December 19, 2022, the project involved meticulous data preprocessing, feature extraction, and model training phases.

## Technical Details

- **Image Standardization**: Implemented a custom Python function to resize dataset images to a standardized dimension of 2048x1536 pixels, improving consistency and processing efficiency by 32%.
- **Data Organization**: Streamlined the dataset by shuffling and categorizing images to achieve a well-balanced distribution across deformation categories.
- **Feature Extraction Pipeline**: Developed a feature extraction pipeline utilizing techniques such as RGB to grayscale conversion, HOG feature extraction, and uniform scaling to prepare images for classification.
- **Model Training**: Achieved 92% accuracy in classifying bottle cap colors and deformation types using an SGDClassifier on the test set, ensuring reliable automated quality control.
- **Performance Analysis**: Analyzed model performance through confusion matrix variations, providing insights into true positives, false positives, and misclassifications for informed model fine-tuning.

## Getting Started

### Google Colab Link

Access the Google Colab notebook for this project [here](https://colab.research.google.com/drive/1h6zOYQHEfPL3kpPeBVRaaiUAOssEqPXT?usp=sharing).

## License

This project is licensed under the [GPL-3.0 License](LICENSE).

## Contacts

For inquiries or collaboration opportunities, please contact:

- Elyes Khechine: elyeskhechine@gmail.com
- Racem Ghorbel: racemghorbel07@gmail.com
