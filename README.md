# Lunar Chronology Crater Analysis

## Required Dataset

This code requires [Moon Crater Database v1 Robbins](https://astrogeology.usgs.gov/search/map/Moon/Research/Craters/lunar_crater_database_robbins_2018).

Download the csv [here](https://pdsimage2.wr.usgs.gov/Individual_Investigations/moon_lro.kaguya_multi_craterdatabase_robbins_2018/data/lunar_crater_database_robbins_2018.csv).

## Retrieving packages [(source)](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#building-identical-conda-environments)

To create this spec list as a file in the current working directory, run:

``` PYTHON
conda list --explicit > geo_env_file.txt
```

To use the spec file to create an identical environment on the same machine or another machine:

``` PYTHON
conda create --name myenv --file geo_env_file.txt
```

To use the spec file to install its listed packages into an existing environment:

``` PYTHON
conda install --name myenv --file geo_env_file.txt
```
