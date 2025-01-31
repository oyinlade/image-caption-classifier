# 🖼️ Image Caption Classification
An intelligent system that automatically classifies and generates descriptive captions for images using deep learning.

## ✨ Features 

* Real-time image classification using state-of-the-art deep learning models
* Natural language caption generation
* Support for multiple image formats (JPG, PNG, WebP)
* Easy-to-use REST API
* Batch processing capabilities
* Comprehensive evaluation metrics

## 🚀 Quick Start
Prerequisites

* Python 3.8+
* PyTorch 2.0+
* CUDA-capable GPU (recommended)

## Installation

```bash
# Clone the repository
git clone https://github.com/oyinlade/image-caption-classifier.git

# Navigate to project directory
cd image-caption-classifier

# Install dependencies
pip install -r requirements.txt
```

## Usage
```python
from caption_classifier import ImageCaptionClassifier

# Initialize the classifier
classifier = ImageCaptionClassifier()

# Classify a single image
result = classifier.process_image("path/to/your/image.jpg")
print(f"Caption: {result.caption}")
print(f"Confidence: {result.confidence}")
```

## 🏗️ Project Structure
```bash
image-caption-classifier/
│── src/                  # Source code
│   ├── __init__.py       # Marks it as a package
│   ├── train.py          # Model training script
│   ├── predict.py        # Inference script
│   ├── data_loader.py    # Loads MSCOCO dataset
│   ├── model.py          # Defines the deep learning model
│
│── notebooks/            # Jupyter notebooks for experimentation
│   ├── colab_train.ipynb # Training notebook (Google Colab)
│   ├── colab_test.ipynb  # Testing & visualization notebook
│
│── models/               # Saved trained models 
│   ├── model.pth         # Pretrained model
│
│── requirements.txt      # Dependencies (for local dev)
│── README.md             # Documentation
│── .gitignore            # Ignore unnecessary files

```
## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

Fork the Project
1. Create your Feature Branch (git checkout -b feature/AmazingFeature)
2. Commit your Changes (git commit -m 'Add some AmazingFeature')
3. Push to the Branch (git push origin feature/AmazingFeature)
4. Open a Pull Request

## 📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 📚 Citation
If you use this project in your research, please cite:

```
@software{image_caption_classifier,
  author = {Apata Oyinlade},
  title = {Image Caption Classification},
  year = {2025},
  publisher = {GitHub},
  url = {https://github.com/oyinlade/image-caption-classifier}
}
```

## 🙏 Acknowledgments

* Thanks to FastAI for their excellent deep learning library
* The MS COCO dataset team for providing training data
* All contributors and supporters
