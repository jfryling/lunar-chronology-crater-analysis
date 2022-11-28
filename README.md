# Lunar Chronology Crater Analysis

## Retrieving packages: [(source)](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#building-identical-conda-environments)

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
