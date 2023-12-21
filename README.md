Repository for misc. geospatial learnings.

To run the jupyter labs environment:
1. Ensure python 3.10.6 is available on the systeem via pyenv.
```sh
brew install pyenv
pyenv install 3.10.6
pyenv local 3.10.6
```

2. Create a python virtual environment and jupyter kernel.
```sh
# Create the virtual environment, in which the package versions specified in the Pipfile will be installed
pipenv install --python 3.10.6

# Activate the virtual environment
pipenv shell

# Create a jupyter kernel tied to the active python virtual environment
# if you don't already have a suitable one.
# python -m ipykernel install --user --name=geo
```

3. Start the jupyter lab: jupyter lab.


