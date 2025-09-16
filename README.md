# WMH-seg: 

## A Robust Automated Segmentation Method for White Matter Hyperintensity of Vascular-origin

### Installation
To get started, it's recommended to create a Python (preferably v3.6) environment using either Conda or venv. This helps to manage dependencies and ensure a consistent runtime environment.

We run our WMH-seg on a system running Ubuntu 18.01, with Python 3.6, PyTorch 1.8.1, and CUDA 10.1. 

Once environment is active, install the required packages from `requirements.txt` using pip:
```
pip install -r requirements.txt
```
### Dataset Preparation

Dataset Preparation: please refer to [nn-UNet](https://github.com/MIC-DKFZ/nnUNet/blob/master/documentation/dataset_format.md) and [nnFormer](https://github.com/282857341/nnFormer)

Make your data in the following structure:

    DATASET/
    ├── WMH_raw/
    │   ├── WMH_raw_data/
    │   │   ├── Task01_WMH/
    │   │   │   ├── imagesTr/
    │   │   │   ├── imagesTs/
    │   │   │   ├── labelsTr/
    │   │   │   ├── labelsTs/
    │   │   │   ├── dataset.json

### Trained Models
Trained models are available at: [Google Drive](https://drive.google.com/file/d/1OjS4nYBSqPFRSmn8MCzCh6gUaa77EvmK/view?usp=sharing)

### Acknowledgement
We sincerely appreciate [nn-UNet](https://github.com/MIC-DKFZ/nnUNet/blob/master/documentation/dataset_format.md) and [nnFormer](https://github.com/282857341/nnFormer) for their awesome codebases.

Updating... 
The dataset will be released via the Zenodo repository:(DOI: 10.5281/zenodo.15221380)
