FROM pangeo/pangeo-notebook:master

RUN conda install -y -c conda-forge nodejs
RUN pip install -U pip wheel setuptools jupyter_packaging
RUN pip install git+https://github.com/ian-r-rose/dask-labextension.git@only-check-json-endpoint
