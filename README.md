# DECeNT - Preprocessing Notebooks

This repository is part of the Deep Learning for automatic tExtile iNspection (DECeNT) project, which focuses on defect detection in fabrics using Deep Learning techniques. It contains the notebooks used for data preprocessing before their use in deep learning models.

## Contents

- **notebooks/**  
  Contains Jupyter notebooks with the following steps:
  
  - **Notebook 1: Conversiion directa 8bits.ipynb**  
   Converts the original 16-bit images to 8-bit, making them suitable for further processing.
    
  - **Notebook 2: Renombrar imagenes.ipynb**  
    Renames images located in the "20221124 SARGA 8 bits" directories, adjusting their names to follow the required standard format.
    
  - **Notebook 3: Extraer subimagenes.ipynb**  
    Extracts fixed-size sections (sub-images) from preprocessed images, facilitating detailed analysis of specific regions in both defective and non-defective areas.

  - **Notebook 4: move_cases.ipynb**  
    Moves files from a source directory (search_folder) to a subfolder named 'cases' within the same directory. For each file listed in the patch_name column of the CSV file, it checks if the file exists in the source directory.

  - **Notebook 5: Generar CSV a partir de carpetas controls y cases.ipynb**  
    Generates a CSV file from the files contained in the 'controls' and 'cases' folders.
  
- **README.md**  
  This file describes the repository.

## Use

1. **Cloner the repository**:
   ```bash
   git clone https://github.com/gicap-ubu/dif_textile.git
   cd dif_textile

2. **Install dependencies**:
   
   The required Python packages are:
   
   * opencv-python
   * matplotlib
   * numpy
   * Pillow
   * scikit-image
   * pandas
   * imageio
   * shutil
   * glob
   * os
     
## Dataset
  The dataset can be downloaded from this link: http://hdl.handle.net/10259/9965 
