# ANLP-FINAL
### Nedim Azar - 2728313
Python: `3.8.10`

## Repo Structure
* Each notebook under `src` represents a broad capability being tested, and contains one or more tests.
  * Each test deals with a specific capability of an SRL system.
* The Challenge Sets are contained in `src/data`, and are named accordingly.
* The `src/model_outputs` directory conntains the outputs of the BERT and BiLSTM based models.
  * This directory will be overriden when you run the notebooks.

## Set-Up:
1. Create a virtual environment and activate it: `python3.8 -m venv venv && source venv/bin/activate`
2. Install the requirements: `pip install -r src/requirements.txt`
   * Pip freeze was used for the requirements, but only what is necessary is included.
3. Create an IPython kernel: `python -m ipykernel install --user --name=allenNLP`

## To Run The Notebooks:
1. `jupyter notebook src/[NOTEBOOK]`
2. In the toolbar: `Kernel` > `Change kernel` > `allenNLP`
3. You can now run the notebooks as usual!