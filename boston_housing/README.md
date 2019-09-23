# Requirements

- [RapidMiner Studio](https://rapidminer.com/products/studio/)
- [Python Scripting Extension](https://marketplace.rapidminer.com/UpdateServer/faces/product_details.xhtml?productId=rmx_python_scripting)
- Python installation (this examples uses [Anaconda](https://www.anaconda.com/distribution/))

To setup the required python environment using anaconda, create a new environment based on the `environment.yml` file. This demo only uses matplotlib, pandas and sklearn, so chances are you already have an environment with those libraries installed.

```conda env create -f environment.yml```

# Usage

1. Create a new RapidMiner process.
2. Add the `Execute Python` operator.
3. Point the `script file` parameter to the jupyter notebook provided in this repository.
4. In the `Show Preview...` menu available through the parameter panel, click on one cell containing the `prototyping` tag to deselect it.
5. Execute the process.

## Python Environment
In case your standard Python environment setup in RapidMiner doesn't provide the needed libraries, please create one using the command listed under requirements.

You have multiple options of selecting the newly generated environemnt inside RapidMiner:

- Change the general Python environemnt under `Preferences...` - `Python Scripting` or disable the `use default python` checkbox of the `Execute Python` operator you are using. In both scenarios you can choose from which package manager you'd like to select the environment and which environment in particular to use.