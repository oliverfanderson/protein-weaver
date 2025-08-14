# Python Flask Server

This server is responsible for doing the protein prediction calculation. This server uses another port and the express.js server acts as a main server that will call the APIs in the flask server

## Setup
1. Install Conda
2. Open up terminal and go to the python_api directory
3. Do `conda env create -f environment.yml` to create the conda environment
    - If you have an M4 Mac Chip, use the `environment_m4.yml` file.
4. Activate the conda environment
5. Do `python app.py` to run the server