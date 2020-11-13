# PythonLearning
**Cretaing Virtual env**
  1) create the folder 
  2) locate path in command promt 
  3) virtualenv env
 **An virtual env has been created**
 
 **Activate Virtual Env**
      goto env folder -scripts and type activate
 
 pip install flask -- for pip installation
 
 version check for pip> pip --version
 
 **Update global python pip**
  python -m pip install --upgrade pip


**https://pipenv-fork.readthedocs.io/en/latest/basics.html#:~:text=You%20can%20also%20specify%20%24%20pipenv,pinned%20versions%20in%20your%20Pipfile.**

**PIPENV**
In the project directory, from the command prompt: 
**pip install pipenv**
In the project directory, from the command prompt:
**pipenv shell**
This will create a specific environment for your project, into which pip components will be installed, which will prevent the components being used on this project from impacting or being included in other projects. This should be called before any work is done on your project from the command prompt.

If you already have a Pipfile or are starting to add to one, from the command prompt:
**pipenv install**
