# Requirements

- [RapidMiner Studio](https://rapidminer.com/products/studio/)
- [Python Scripting Extension](https://marketplace.rapidminer.com/UpdateServer/faces/product_details.xhtml?productId=rmx_python_scripting)
- Python installation (this examples uses [Anaconda](https://www.anaconda.com/distribution/))

To setup the required python environment using anaconda, create a new environment based on the `environment.yml` file.

```conda env create -f environment.yml```

# Usage

1. Create a new RapidMiner process.
2. Add the `Execute Python` operator.
3. Point the `script file` parameter to the jupyter notebook provided in this repository.
4. In the `Show Preview...` menu available through the parameter panel, click on one cell containing the `prototyping` tag to deselect it.
5. Execute the process.