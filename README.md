## Projects

- **Iris Classification** – exploratory data analysis and classification models on the Iris dataset.
- **California Housing** – regression models predicting median house values from California census data.

## Setup

Each project has its own conda environment, defined in its `environment.yml`.

1. Install [Miniconda](https://docs.conda.io/en/latest/miniconda.html).
2. Create the environment for the project you want to run:
```
   conda env create -f ml-iris/environment.yml
   conda env create -f california-housing-ml/environment.yml
```
3. Activate it:
```
   conda activate ml-iris
```
4. Open the project's notebook in VS Code or Jupyter and select the matching kernel.

To update an environment after changing its `environment.yml`:
```
conda env update -f <project>/environment.yml --prune
```