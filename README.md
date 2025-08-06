## Wildfire Detection and Segmentation

This repository implements the framework described in  
**Unifying Classification and Segmentation in Wildfire Detection**  
_S. Singh, V. Vazirani, and A. Singhania, Multimedia Tools and Applications, 2024._

A unified deep learning pipeline for:  
- **Fire Classification**: Detect presence or absence of fire in aerial images.  
- **Pixel-wise Segmentation**: Precisely localize fire regions using segmentation masks.

## Features

- **End-to-End Pipeline**: From data preprocessing to model inference.  
- **Modular Codebase**: Separate modules for dataset handling, model architectures, training, and inference.  
- **Pre-trained Checkpoints**: Ready-to-use model weights included.  
- **Evaluation Scripts**: Compute IoU, Precision, Recall, and F1-score.

## Repository Structure

├── data/
│ ├── raw/ # Original images and annotation masks
│ └── processed/ # Resized images, masks, and train/val splits
├── notebooks/ # Exploratory analyses and visualizations
├── models/ # Saved model checkpoints
├── src/
│ ├── dataset.py # Dataset loading, preprocessing, and augmentation
│ ├── model.py # Network architectures (e.g., U-Net variants)
│ ├── train.py # Training routines and logging
│ ├── infer.py # Inference and visualization
│ └── evaluate.py # Evaluation metrics scripts
├── requirements.txt # Python dependencies
└── README.md # Project overview and instructions


## Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/The-Swapster/Wildfire-Detection-and-Segmentation.git
   cd Wildfire-Detection-and-Segmentation
   ```
   
2. Create and activate a virtual environment
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
   
3. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

Citation

If you use this work in your research, please cite:

    Singh, S., Vazirani, V., Singhania, S. et al. Beyond boundaries: Unifying classification and segmentation in wildfire detection systems. Multimed Tools Appl 84, 22441–22473 (2025). https://doi.org/10.1007/s11042-024-19888-0

License

This project is licensed under the MIT License. See LICENSE for details.
Contact

For questions or contributions, please open an issue or contact us
Swapnil Singh (swapnilsingh@outlook.in).


