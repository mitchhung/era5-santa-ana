# era5-santa-ana

How to get up and running:

1. Install mamba. Installation instructions [here](https://mamba.readthedocs.io/en/latest/installation/mamba-installation.html)
2. Create a python environment with `mamba env create -f env.yaml`
3. Activate it with `mamba activate xr-era5` 
4. Install xarray with `python -m pip install "xarray[complete]"`
4. Start a Jupyter server with `jupyter notebook`
5. I've provided a tutorial notebook. There are also other GCP/ERA5 tutorials available at https://github.com/google-research/arco-era5/tree/main/docs

Additional tutorials are listed below. You can't load data in the way that they do, but they should give you ideas on how you can manipulate the data.
- https://github.com/planet-os/notebooks/blob/master/api-examples/ERA5_tutorial.ipynb
- https://github.com/planet-os/notebooks/blob/master/aws/era5-s3-via-boto.ipynb
