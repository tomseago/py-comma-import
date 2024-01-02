# py-comma-import
Imports / Updates the latest openpilot list of supported cars into a notion database

----

# Development Notes

## Updating the environment.yml file

The following will export the current conda environment, including the currently installed pip packages, to the `environment.yml` file, which should then be updated into github.

    conda env export > environment.yml

