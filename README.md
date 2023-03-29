# netdata-gpt-notebooks

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/andrewm4894/netdata-gpt-notebooks/HEAD)

Notebooks for playing around with Netdata and GPT

## Usage

### Locally

Recommended to use VSCode with the [Jupyter extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) installed as will make things much easier.

1. clone the repo and cd into it.
2. create a virtual environment `python -m venv venv`.
3. activate the virtual environment `source venv/bin/activate` (or use vscode and select the venv as the python interpreter).
4. install the requirements `pip install -r requirements.txt`.
5. create a `.env` file based off of the `.env.example` file and fill in the details.
6. see if you can run the minimal example notebook `notebooks/minimal_data_example.ipynb`.

### Binder

Press the binder "launch" button above to launch and run the notebooks in this repo in the cloud on binder.

### nbviewer

If you just want to read the notebooks then nbviewer is much nicer - you can see the notebooks via nbviewer at https://nbviewer.jupyter.org/github/andrewm4894/netdata-gpt-notebooks/tree/main/notebooks/

## Notebooks

- [minimal_data_example.ipynb](https://github.com/andrewm4894/netdata-gpt-notebooks/blob/main/notebooks/minimal_data_example.ipynb): A minimal example of pulling some chart data and asking a gpt model if it looks ok.
