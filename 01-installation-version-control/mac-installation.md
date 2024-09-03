# Python Installation

This tutorial will go over how to install CPython on **Mac**. 

### Download CPython
Download CPython from the [official Python website](https://www.python.org/). As noted in the [documentation](https://docs.python.org/3/) (Fig 1), Python 3.12 is the latest stable version. Thus, you should download Python **3.12**, which is also the automatic recommendation on the download page (Fig 2).

<figure>
  <img src="mac-installation-images/version.png" alt="Python 3 versions" width="125">
  <figcaption>Fig 1. Python 3 versions from documentation</figcaption>
</figure>

<figure>
  <img src="mac-installation-images/download.png" alt="Python 3 download page" width="450">
  <figcaption>Fig 2. Python 3 download page</figcaption>
</figure>

### Install CPython
Click on the download .pkg file and follow the instructions to install CPython (Fig 3).

<figure>
  <img src="mac-installation-images/install.png" alt="Python 3.12 install" width="225">
  <figcaption>Fig 3. Python 3.12 installaer</figcaption>
</figure>

Upon completing the installation, the executable file that launches Python is typically located in the `/usr/local/bin` directory. This directory is commonly used for storing executables installed by the user. Running the command `ls /usr/local/bin/python3*` in the terminal shows that Python 3.12 executable is indeed inside `/usr/local/bin`. (Fig 4). You can also see that I have also installed 3.11 before.

<figure>
  <img src="mac-installation-images/executable.png" alt="Python 3.12 executable" width="500">
  <figcaption>Fig 4. Python 3.12 executable</figcaption>
</figure>