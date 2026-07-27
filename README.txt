# Interactive Population Visualization of Virginia  
### Built with VTK, Trame, and Vega-Altair

This project is an interactive visualization system designed to explore county-level population trends in Virginia from 2010–2019. The application combines:

- **VTK** for rendering the Virginia county map  
- **Trame** for server–client communication and UI  
- **Vega-Altair** for analytical visualizations  
- **Machine Learning** tools (K-Means, PCA, Linear Regression)  
- **Pandas + NumPy** for data processing  

Users can interactively view population trends, compare counties, explore demographic similarity, analyze yearly growth correlations, visualize clusters, and forecast future population trends.

---

## Getting Started

### **1. Create Virtual Environment (Recommended)**

```bash
python3 -m venv venv
source venv/bin/activate        # macOS / Linux
venv\Scripts\activate           # Windows


### Install Dependencies

pip install -r requirements.txt


### Inside the src folder:
python app.py


Trame will start a local web server — the terminal will show a URL such as:

http://localhost:1234/



Data Requirements

Your data/ folder must contain:

virginia_population.csv — 133 counties × years 2010–2019

virginia_counties.vtp — VTK PolyData of Virginia counties

These files are automatically loaded by data_loader.py


