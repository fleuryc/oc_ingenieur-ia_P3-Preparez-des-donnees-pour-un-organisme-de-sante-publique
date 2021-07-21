[![Codacy Badge](https://app.codacy.com/project/badge/Grade/dbacd5a1e5a64c41875d250d7eac59c0)](https://www.codacy.com/gh/fleuryc/oc_ingenieur-ia_P3-Preparez-des-donnees-pour-un-organisme-de-sante-publique/dashboard)

# Open Food Facts : help French Public Health Agency use Open Data

Repository of OpenClassrooms' [AI Engineer path](https://openclassrooms.com/fr/paths/188-ingenieur-ia), project #3

Goal : use Jupyter Notebook and Voilà to clean, analyse and present Open Food Facts open data, in order to help French Public Health Agency use this data efficiently.

## Requirements

-   Conda

````bash
# conda install jupyterlab ipywidgets numpy pandas matplotlib seaborn plotly statsmodels sklearn
# conda install -c conda-forge voila
# or :
conda env update -f environment.yml
````

-   Pip

```bash
# pip install jupyterlab ipywidgets numpy pandas matplotlib seaborn plotly statsmodels sklearn voila
# or :
pip install -r requirements.txt
```

## Troubleshooting

-   Fix Plotly issues with JupyterLab

cf. [Plotly troubleshooting](https://plotly.com/python/troubleshooting/#jupyterlab-problems)

```bash
jupyter labextension install jupyterlab-plotly
```

-   If using Jupyter Notebook instead of JupyterLab, uncomment the following lines in the notebook

````python
import plotly.io as pio
pio.renderers.default='notebook'
````
