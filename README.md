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
$ tree
.
├── Images with Boxed areas/    # Annotated bounding box images
├── Images/                     # Raw aerial fire images
├── Masked Images/              # Segmentation masks for preprocessing
├── Notebooks/                  # Jupyter notebooks for experiments
│   ├── AlexNet_fire_cnn.ipynb
│   ├── SegNet.ipynb
│   ├── UNet.ipynb
│   ├── extraction_and_segmentation.ipynb
│   └── image_cleaning.ipynb
├── Original Images/            # Unmodified source images
├── Segmented Images/           # Model inference outputs
├── src/                        # Core implementation modules
│   ├── dataset.py              # Data loading and augmentation
│   ├── model.py                # Network architectures
│   ├── train.py                # Training routines
│   ├── infer.py                # Inference scripts
│   └── evaluate.py             # Evaluation metrics
├── requirements.txt            # Python dependencies
├── .gitignore                  # Ignored files (e.g., .DS_Store)
└── README.md                   # Project overview and instructions


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


