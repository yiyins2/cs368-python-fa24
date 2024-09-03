# Virtual Environments

This tutorial will go over how to create and then activate/deactivate a virtual environment.

### Creating Virtual Enviroment
There are many virtual environment management tools; we will use `venv` in this course, which is already included in the standard library upon installation. You're welcome to use other tools, such as Conda, pyenv, or virtualenv.

In your terminal ...

1. `cd` into a directory that you want to use for CS368 development.

2. Use `pwd` to make sure you're in the correct directory.

3. Create the virtual environment with the command in the format of: 

    ```<python version/path> -m venv <venv_name>``` 

    * Mac users need to use the Python version, e.g., `python3.12`.
    * Windows users need to specify the entire path to your Python3.12 executable. 

    We'll use Python 3.12 for this course, and I'll name my virtual environment 'py3.12', so the filled-in command will be:

    * `python3.12 -m venv py3.12` for Mac
    * `C:\Path\To\Python3.12\python.exe -m venv py3.12` for Windows

4. Once the virtual environment is created, you'll see a copy of Python 3.12 is created under your current directory (Fig for Mac and Fig for Windows). 

### Activate/Deactivate Virtual Environment
You can activate your virtual environment with the command:
* ```source <venv_name>/bin/activate``` for Mac
* ```.\<venv_name>\Scripts\activate``` for Windows

My virtual environment is named 'py3.12', so the filled-in command will be:
* ```source py3.12/bin/activate``` for Mac
* ```.\py3.12\Scripts\activate``` for Windows

Once you enter a virtual environment, a green `(venv_name)` will appear indicating you're under this virtual environment (Fig for Mac and Fig for Windows).

Windows: if you encountered the following error after activated your venv, run `Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted` to resolve.

<figure>
  <img src="windows-installation-images/venv.png" alt="Python 3.12 executable" width="500">
  <figcaption>Fig . Virtual environment</figcaption>
</figure>

You can simply run `deactivate` to exit the current virtual enviroment.