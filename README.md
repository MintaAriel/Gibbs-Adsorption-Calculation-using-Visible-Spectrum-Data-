# Mo/W-CNT Adsorption Analysis

🔬 **UV-Vis Spectral Analysis of Molybdenum/Tungsten Systems for Carbon Nanotube Adsorption Characterization**

This repository analyzes spectral data from a **Leki SS2110 UV-Vis spectrophotometer** to quantify Gibbs excess adsorption (Γ) of Molybdenum/Tungsten (Mo/W) oxide systems on carbon nanotubes (CNTs). The workflow processes optical absorbance spectra (400-1100nm) to:

1. Calculate excess adsorption using concentration-dependent UV-Vis measurements  
2. Model adsorption behavior through Langmuir isotherm analysis    

## Key Features
- **Automated spectral processing** with `UVVisAnalyzer` class  
- **Adsorption isotherm modeling** using `Isotherm` class  
- **Gibbs adsorption calculation**
- **Data claening** using pandas  

📊 **Datasets**: Includes raw spectral files (CSV) organized by:
- Mo/W ratio (95/5)  
- pH conditions (0.5,2,3.11)  
- Mo/W concentrations (0.02-0.1 wt%)  

🔧 **Technology Stack**: Python • pandas • NumPy  • matplotlib   
