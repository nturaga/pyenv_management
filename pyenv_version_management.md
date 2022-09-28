# Manage versions of python with pyenv

https://realpython.com/intro-to-pyenv/#using-pyenv-to-install-python

## Get vesions

	pyenv versions
	
## Set global version to non-system version of Apple python

	pyenv global 3.10.4
	
## test installated version of python 3.10.4

	python -m test
	
## pyenv commands - list all commands in pyenv

	pyenv commands
	
## EMACS - use elpy

This will activate a python shell, but not a virtualenv

	M-x run-python
	
	M-x pyvenv-workon
	
	M-x pyvenv-activate
	
	M-x pyvenv-deactivate

## Virtualenvs and pyenv

**pyenv** manages multiple versions of Python itself.

**virtualenv/venv** manages virtual environments for a specific Python
version.

**pyenv-virtualenv** manages virtual environments for across varying
versions of Python.
