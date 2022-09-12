# if jupyter notebook is needed, that's what this environment maintains

## _n.b._
* It is assumed that this will be maintained within PyCharm for Windows & anaconda is already installed, and related functionality is assumed

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

## possible future work
* Intelij has a whole IDE for "jupyter stuff"
* Commercial version(s) of this or other InteliJ products have more intercompatibility
* Additionally, commercial PyCharm has more explicit notebook integration

## contact information
b.dewhirst@gmail.com