In the notebook 02_Weather Analysis.ipynb, if you try to plot more/all stations in the world, you could run into IOpub datarate exceeded error. To fix that you can either change the jupyter config or use command "jupyter notebook --NotebookApp.iopub_data_rate_limit=1.0e10" while starting the notebook.

For reference:
* https://github.com/jupyter/notebook/issues/2287
* https://media.readthedocs.org/pdf/jupyter-notebook/latest/jupyter-notebook.pdf

