Baseline benchmark for 2019
===========================

This is the baseline benchmark we want to use for 2019. Using Parquet
files to load and store data is currently my default suggestion when
people ask for an efficient workflow.

The benchmark is split up into 

Setup
-----

This environment was created and activated using

```
conda create -p dsib-baseline-2019 python=3.6 pyarrow=0.11.1 pandas=0.23.4 jupyterlab -c conda-forge
source activate $(pwd)/dsib-baseline-2019
```

You can find the exact version numbers of the packages in `frozen-conda-env`.