# Mouse Hippocampal Brain Stack Dataset
**A Dataset for Pixel-Wise, Cluster-Based Non-Rigid 3D Registration of Microscopic Images**

## Description
This repository contains the Mouse Hippocampal Brain Stack dataset, developed to support research on 3D reconstruction and non-rigid registration methods. The dataset comprises of two main folders, Raw and Series. "Raw" contains all raw images while "Series" contains 10 high-resolution image pairs (1300 × 2000 pixels) of serial-section microscopic images, focusing on the hippocampal region of the mouse brain. It is designed to evaluate algorithms tackling challenges such as tissue distortions, staining inconsistencies, and complex spatial deformations.

## Dataset Structure
```
.
├── Mouse_Hippocampal_Brain_Stack/
│   ├── Raw/
│   ├── Series/
│   │   ├── 111.jpg
│   │   ├── 113.jpg
│   │   ├── 121.jpg
|   |   └──...
└── README.md
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mouse-brain-stack.git
   ```

2. Load images using your preferred image processing library (e.g., OpenCV, scikit-image, or PIL).

3. Use this dataset for testing non-rigid registration algorithms or 3D reconstruction methods.

## Licensing
This dataset is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license. You are free to:

- **Share**: Copy and redistribute the material in any medium or format.
- **Adapt**: Remix, transform, and build upon the material for any purpose, even commercially.

**Under the following terms:**

- **Attribution**: You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

For details, see the full license text here: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).


## Citation
The result are going to be submitted to IEEE transactions on Computational Imaging. Citation will be available after submission.

## Contact
For any questions or issues regarding this dataset, please contact:
- **Name**: Parsa Mojarad Adi
- **Email**: parsa.78.99@gmail.com
- **Affiliation**: Shahid Beheshti University

