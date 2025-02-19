Example of Bokeh tutorial running in a pyodide kernel in JupyterLite.

Deployed to github pages at https://ianthomas23.github.io/bokeh-tutorial-pyodide

To try out locally, create a python virtual environment of your choice (`venv`, `pyenv`,
'mamba', `conda`, etc) and follow these steps:

```bash
python -m pip install -r requirements.txt
jupyter lite build --contents notebooks
jupyter lite serve
```

and open a web browser at the URL specified.
