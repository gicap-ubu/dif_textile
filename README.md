# DECeNT - Preprocessing Notebooks

Este repositorio forma parte del proyecto **Deep Iearning for automatic tExtile iNspection (DECeNT)**, orientado a la detección de defectos en telas mediante técnicas de Deep Learning. Aquí se encuentran los notebooks utilizados para el preprocesamiento de datos antes de su uso en modelos de aprendizaje profundo.

## Contents

- **notebooks/**  
  Contains Jupyter notebooks with the following steps:
  
  - **Notebook 1: Conversión de Imágenes (16 bits a 8 bits)**  
   Converts the original 16-bit images to 8-bit, making them suitable for further processing.
    
  - **Notebook 2: Renombrado de Imágenes**  
    Renames images located in the "20221124 SARGA 8 bits" directories, adjusting their names to follow the required standard format.
    
  - **Notebook 3: Extracción de Subimágenes**  
    Extracts fixed-size sections (sub-images) from preprocessed images, facilitating detailed analysis of specific regions in both defective and non-defective areas.
  
- **README.md**  
  This file describes the repository.

## Use

1. **Cloner the repository**:
   ```bash
   git clone https://github.com/gicap-ubu/DECeNT-preprocessing.git
   cd DECeNT-preprocessing

2. **Install dependencies**:
   
   The required Python packages are:
   
   * opencv-python
   * matplotlib
   * numpy
   * Pillow
   * scikit-image
   * pandas
   * imageio
     
## Dataset
  The dataset can be downloaded from this link: http://hdl.handle.net/10259/9965 
