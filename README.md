# san_francisco_housing
**Jupyter notebook analyzing housing rental market data with interactive visualizations using PyViz, Plotly, and the Mapbox API.**

---
## Tools
- PyViz
- The Mapbox API

## Installation Instructions
### Create a new conda environment to avoid conflicts with other package installations:
```powershell
conda deactivate
```
```powershell
conda update conda
```
```powershell
conda create -n pyviz python=3.7 anaconda
```
```powershell
conda activate pyviz
```
### Install PyViz packages:
```powershell
conda install -c plotly plotly=4.13.
```
```powershell
conda install -c pyviz hvplot
```
- PyViz require NodeJS version >= 12
```powershell
conda install -c conda-forge nodejs=12
```
### Install required JupyterLab Dependencies:
```powershell
conda install -c conda-forge jupyterlab=2
```
```powershell
jupyter labextension install jupyterlab-plotly@4.13.0 --no-build
```
```powershell
jupyter labextension install @jupyter-widgets/jupyterlab-manager plotlywidget@4.13.0 --no-build
```
```powershell
jupyter labextension install @pyviz/jupyterlab_pyviz --no-build
```
```powershell
jupyter lab build
```
### Install python-dotenv
```powershell
pip install python-dotenv
```

---
## Examples
![Housing Units Sold by Year](Images/zoomed-housing-units-by-year.png)
![Average Sale Price per Sq Ft and Gross Rent](Images/avg-sale-px-sq-foot-gross-rent.png)
![Prices by Year by Neighborhood](Images/pricing-info-by-neighborhood.png)
![Geoviews Plot](Images/6-4-geoviews-plot.png)
![Interactive Map 1](Images/mapbox_output.png)

---
## Contributors
Initial contribution Avangelina Cazares. Open source.

---
## License
None.