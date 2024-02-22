Overview
The script aims to preprocess Sentinel images by masking out clouds and shadows, followed by the calculation of NDVI, which is a commonly used index to quantify vegetation health and density.

Usage
To use the script, follow these steps:

Ensure you have Python 3 installed on your system.
Install the required dependencies listed in the "Dependencies" section.
Update the script with your desired parameters, such as start date, end date, and coordinates defining the area of interest.
Run the script using the command python script_name.py.
Functionality
Cloud Masking: The script utilizes Landsat images to mask out clouds and shadows, ensuring that only clear pixels are used for further analysis.
NDVI Calculation: After cloud masking, the script calculates the Normalized Difference Vegetation Index (NDVI) for each pixel in the images, providing valuable information about vegetation health and density.
Dependencies
Earth Engine Python API: Python library for interacting with Google Earth Engine.
NumPy: Library for numerical computing in Python.
SciPy: Library for scientific computing and interpolation.
Author
Your Name - Initial work
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
This script was inspired by the need for preprocessing Landsat imagery for vegetation analysis.
