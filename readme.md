### Introduction

Kaggle examples aims at providing notebook/script examples for Kaggle competitions

### Installation requirements

Some of the examples may use H2O4GPU or Datatable, here are some simple installation steps.

```
# Create a virtualenv
virtualenv -p python3.6 h2o4gpuenv
# source env
. h2o4gpuenv/bin/activate
# Get H2O4GPU wheel for ubuntu, see repo for latest files
# I'm on CUDA10
wget https://s3.amazonaws.com/h2o-release/h2o4gpu/releases/stable/ai/h2o/h2o4gpu/0.3-cuda10/h2o4gpu-0.3.2-cp36-cp36m-linux_x86_64.whl
# Install H2O4GPU
pip install h2o4gpu-0.3.2-cp36-cp36m-linux_x86_64.whl
# Install Datatable
pip install https://s3.amazonaws.com/h2o-release/datatable/stable/datatable-0.8.0/datatable-0.8.0-cp36-cp36m-linux_x86_64.whl
```

You may want to visit the installation pages directly for more in depth understanding or finding the installation that best fits your needs.
