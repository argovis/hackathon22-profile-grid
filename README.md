# Argovis Hackathon 2022 - Profile Data on Regular Grids Group

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/argovis/hackathon22-profile-grid/HEAD)

Here's a mostly-empty repo for your group to collect their work in. Some notes:

 - the `environment.yml` file is the same one the Argovis team uses to set up its notebooks, and is a good starting place to begin building from. Click on the Binder badge above to be taken to a working Jupyter notebook environment, or use it to start your own environment locally if you're familiar with conda and notebooks.
 - See https://argovis.github.io/hackathon22-docs/index.html for docs on Argovis' API, datastructures, and other useful info.
 - Instructions are listed below to create an environment from a .yml file, make that environment available when using jupyter, and start jupyter (if you start jupyter within the folder where your notebook is, you can then open the notebook and run it, after selecting the right kernel).
   - run these commands from the terminal (jupyter and conda need to be installed)
``` 
conda env create -f environment.yml
conda activate argovis_demos
conda install -c anaconda ipykernel
python -m ipykernel install --user --name=argovis_demos
conda deactivate
jupyter notebook & (then select the right kernel to run the notebook)
```
