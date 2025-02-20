# DECeNT - Preprocessing Notebooks

Este repositorio forma parte del proyecto **Deep Iearning for automatic tExtile iNspection (DECeNT)**, orientado a la detección de defectos en telas mediante técnicas de Deep Learning. Aquí se encuentran los notebooks utilizados para el preprocesamiento de datos antes de su uso en modelos de aprendizaje profundo.

## Contenido

- **notebooks/**  
  Contiene los cuadernos de Jupyter con los siguientes pasos:
  
  - **Notebook 1: Conversión de Imágenes (16 bits a 8 bits)**  
    Convierte las imágenes originales de 16 bits a 8 bits, adecuándolas para su procesamiento posterior.
    
  - **Notebook 2: Renombrado de Imágenes**  
    Renombra las imágenes ubicadas en los directorios de "20221124 SARGA 8 bits", ajustando sus nombres para que sigan el formato estándar requerido.
    
  - **Notebook 3: Extracción de Subimágenes**  
    Extrae secciones (subimágenes) de tamaño fijo de las imágenes preprocesadas, facilitando el análisis detallado de regiones específicas en áreas defectuosas y no defectuosas.
  
- **README.md**  
  Este archivo que describe el repositorio.

## Uso

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/gicap-ubu/DECeNT-preprocessing.git
   cd DECeNT-preprocessing

2. **Instalar dependencias**:
   
   Los paquetes de Python utilizados son:
   
   * opencv-python
   * matplotlib
   * numpy
   * Pillow
   * scikit-image
   * pandas
   * imageio
     
## Dataset
