# Python Installation

This tutorial will go over how to install CPython on **Windows**. 

### Download CPython
Download CPython from the [official Python website](https://www.python.org/). As noted in the [documentation](https://docs.python.org/3/) (Fig 1), Python 3.12 is the latest stable version. Thus, you should download Python **3.12**, which is also the automatic recommendation on the download page (Fig 2).

<figure>
  <img src="mac-installation-images/version.png" alt="Python 3 versions" width="125">
  <figcaption>Fig 1. Python 3 versions from documentation</figcaption>
</figure>

<figure>
  <img src="windows-installation-images/download.png" alt="Python 3 download page" width="450">
  <figcaption>Fig 2. Python 3 download page</figcaption>
</figure>


### Install CPython
Click on the download .exe file and check the **add python.exe to PATH** box at the bottom (Fig 3). Then follow the instructions prompted to install CPython. 

<figure>
  <img src="windows-installation-images/install.png" alt="Python 3.12 install" width="400">
  <figcaption>Fig 3. Python 3.12 installer</figcaption>
</figure>

Upon completing the installation, the directory containing the Python files, including the executable, is typically located in the `AppData\Local\Programs` directory. Running the commands `cd AppData\Local\Programs\Python` followed by `ls` in Windows PowerShell to list all previously installed Python versions. You will see that 3.12 is indeed in this folder (Fig 4), along with 3.11, which I had installed earlier.

<figure>
  <img src="windows-installation-images/path.png" alt="AppData\Local\Programs\Python folder" width="500">
  <figcaption>Fig 4. AppData\Local\Programs\Python folder </figcaption>
</figure>

Once you `cd Python312` and then `ls`, you’ll find that `python.exe` is the executable that comes with the installation (Fig 5). You can also run `python.exe --version` to verify that this executable can successfully be run.

<figure>
  <img src="windows-installation-images/executable.png" alt="Python 3.12 executable" width="500">
  <figcaption>Fig 5. Python 3.12 executable</figcaption>
</figure>

You can also see that the Python 3.12 executable is added to the `PATH` environment variable after installation by running `$env:PATH` (Fig 6).

<figure>
  <img src="windows-installation-images/path-var.png" alt="path variable" width="500">
  <figcaption>Fig 6. PATH environment variable</figcaption>
</figure>

