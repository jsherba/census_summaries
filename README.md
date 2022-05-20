# Census data summaries for 2000, 2010, 2020 census

Summaries for 2010 and 2020 are derived from the [American Community Survey](https://www.census.gov/programs-surveys/acs). Year 2000 summaries are derived from the 2000 decentenial census. Tract level socio-economic data is summarized for three geographies: 1-mile radius, closest tracts, tenderloin/SoMA neighborhoods.   

## Installation

Set up a [Python virtual environment](https://docs.python.org/3/library/venv.html) and activate

```bash
pip install virtualenv
python3 -m venv /path/to/new/virtual/environment/env
source env/bin/activate
```

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install Python packages via requirements.txt.

```bash
pip install requirements.txt
```

To visualzed results on a map the Geopandas Python library is used. Geopandas requires special attention to install on Windows. Install Fiona, GDAL, Geopandas, pyproj, and Shapely via windows Binaries by following the instructions [here](https://towardsdatascience.com/geopandas-installation-the-easy-way-for-windows-31a666b3610f). Alternatively install Geopandas via Conda. 

## Usage

Launch the Jupyter Notebook
```bash
jupyter notebook
```

