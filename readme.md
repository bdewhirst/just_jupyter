# if jupyter notebook is needed, that's what this environment maintains

## requirements
* maintained by pip within conda AFAIK
  * double check if it becomes relevant
* separate requirements for pandas and numpy may be redundant
  * double check if it becomes relevant

## to add an environment
* `python -m ipykernel install --user --name=environmentName`
  * _e.g._ `python -m ipykernel install --user --name=just_jupyter`

## to start jupyterhub
* open anaconda prompt
* enter `jupyter notebook`
* select desired kernel, get started.
* default jupyterhub location:  http://localhost:8888/tree