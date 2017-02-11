#Environment Management on Python
####pip / pyenv / virtualenv / anaconda
- pip: the Python Package Manager
- pyenv: Python Version Manager
- virtualenv: Python Environment Manager
- Anaconda: (distro) Package Manager + Environment Manager + Additional Scientific Libraries (not only for python)
- http://stackoverflow.com/questions/38217545/the-different-between-pyenv-virtualenv-anaconda-in-python

####workflow with pyenv, virtualenv and pip
- install a new python version with pyenv: (installed under ~/.pyenv)
 - `$ pyenv install 3.5`
- change between versions:
 - `$ pyenv global 3.5` or to switch back `$ pyenv global system`
- create new project directory and enter
- create new environment (called .venv) with virtualenv
 - `$ python3.5 -m venv .venv`
- activate new environment
 - `$ source .venv/bin/activate`
- install packages on the new environment with pip
 - `$ pip install ipython`
- http://blog.abraseucodigo.com.br/instalando-qualquer-versao-do-python-no-linux-macosx-utilizando-pyenv.html
- http://blog.abraseucodigo.com.br/virtualenv-pip-pra-que-servem.html#criando-virtualenv-e-utilizando-o-pip-no-linux-e-mac-osx

####workflow with conda
