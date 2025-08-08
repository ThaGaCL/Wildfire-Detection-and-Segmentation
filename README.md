## Wildfire Detection and Segmentation

This repository implements the framework described in
**Beyond boundaries: Unifying classification and segmentation in wildfire detection systems**
_Swapnil Singh, Vidhi Vazirani, Sanvika Singhania, Vaishnavi Singh Suroth, Vaibhav Soni, Ameyaa Biwalkar, and Deepa Krishnan, Multimedia Tools and Applications, 2024._

A unified deep learning pipeline for:

- **Fire Classification**: Detect presence or absence of fire in aerial images.
- **Pixel-wise Segmentation**: Precisely localize fire regions using segmentation masks.

## Features

- **End-to-End Pipeline**: From data preprocessing to model inference.
- **Modular Codebase**: Separate modules for dataset handling, model architectures, training, and inference.
- **Pre-trained Checkpoints**: Ready-to-use model weights included.
- **Evaluation Scripts**: Compute IoU, Precision, Recall, and F1-score.

## Repository Structure

```text
├── Dataset/
│   ├── Images with Boxed areas/
│   ├── Mask Images/
│   ├── Original Images/
│   ├── Segmentation Images/
│   └── Segmented Images/
├── Notebooks/
│   ├── AlexNet_fire_cnn.ipynb
│   ├── SegNet.ipynb
│   ├── UNet.ipynb
│   ├── extraction_and_segmentation.ipynb
│   └── image_cleaning.ipynb
└── README.md
```


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
