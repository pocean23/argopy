# ![argopy logo](https://avatars1.githubusercontent.com/t/3711886?s=90&v=4) Argo data python library

[![Build Status](https://travis-ci.com/euroargodev/argopy.svg?branch=master)](https://travis-ci.com/euroargodev/argopy)

``argopy`` is a python library that aims to ease Argo data access, visualisation and manipulation for regular users as well as Argo experts and operators.

Several python packages exist: we are currently in the process of analysing how to merge these libraries toward a single powerfull tool. [List your tool here !](https://github.com/euroargodev/argopy/issues/3)

## Install

Since this is a library in active development, use direct install from this repo to benefit from the last version:

```bash
pip install git+http://github.com/euroargodev/argopy.git@master
```

## Examples

Examples of data fetching, manipulation and visualisation are available on the [erddap examples repository](https://github.com/euroargodev/erddap_usecase).

You can run and test live example notebooks here:
[![badge](https://img.shields.io/badge/launch-Pangeo%20binder-579ACA.svg?logo=data:image/png;base64,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)](https://binder.pangeo.io/v2/gh/euroargodev/erddap_usecases/master) (thanks [Pangeo](pangeo.io)) 


## Usage

The primary data model used to manipulate Argo data is [xarray](https://github.com/pydata/xarray).

### Argo Data Fetcher

Init the fetcher:
```python
    from argopy import DataFetcher as ArgoDataFetcher

    argo_loader = ArgoDataFetcher()
    argo_loader = ArgoDataFetcher(backend='erddap')
    argo_loader = ArgoDataFetcher(cachedir='tmp')
```
and then, request data for a domain:
```python
    argo_loader.region([-85,-45,10.,20.,0,100.]).to_xarray()
    argo_loader.region([-85,-45,10.,20.,0,100.,'2012-01','2014-12']).to_xarray()
```
for profiles of a given float: 
```python
    argo_loader.profile(6902746, 34).to_xarray()
    argo_loader.profile(6902746, np.arange(12,45)).to_xarray()
    argo_loader.profile(6902746, [1,12]).to_xarray()
```
or for a collection of floats:
```python
    argo_loader.float(6902746).to_xarray()
    argo_loader.float([6902746, 6902747, 6902757, 6902766]).to_xarray()
    argo_loader.float([6902746, 6902747, 6902757, 6902766], CYC=1).to_xarray()
```

**Development roadmap**:

We aim to provide high level helper methods [(see this milestone)](https://github.com/euroargodev/argopy/milestone/1) to load Argo data from:
- [x] Ifremer erddap
- [ ] local copy of the GDAC ftp folder [(ongoing work)](https://github.com/euroargodev/argopy/pull/5)
- [ ] the argovis dataset [(help wanted)](https://github.com/euroargodev/argopy/issues/2)
- [ ] any other usefull access point to Argo data ?

At this point data are fetched and returned in memory as [xarray.DataSet](http://xarray.pydata.org/en/stable/data-structures.html#dataset). 
From there, it is easy to convert it to other formats like a [Pandas dataframe](https://pandas.pydata.org/pandas-docs/stable/getting_started/dsintro.html#dataframe):
```python
ds = argo_loader.profile(6902746, 34).to_xarray()
df = ds.to_dataframe()
```

and to export it to files:
```python
ds = argo_loader.region([-85,-45,10.,20.,0,100.]).to_xarray()
ds.to_netcdf('my_selection.nc')
# or by profiles:
ds.argo.point2profile().to_netcdf('my_selection.nc')
```

### Argo data manipulation with xarray

The ``argopy`` library provides an xarray accessor named ``argo`` to help manipulate and analyse data.

Example: Convert a collection of points to a collections of profiles:
```python
from argopy import DataFetcher as ArgoDataFetcher
ds = ArgoDataFetcher(ds='bgc').float(5903248).to_xarray()
ds = ds.argo.point2profile()
```
