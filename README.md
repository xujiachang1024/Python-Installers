# Python Installers
Commands to use Anaconda to install Python environments and packages

### How to install Python using `conda`:
0. Open terminal
1. Run the following command to install anaconda
```
conda install conda
```
2. Replace `*`in the following command with the name you choose for this Python environment (e.g. `Py27`, `Py36`, etc.); replace `$` in the following command with the version number of Python environment you want to install (e.g. `2.7`, `3.6`, etc); run the following command to install Python environment with the desired version and name
```
conda create -n * python=$
```
3. Replace `*`in the following command with the name of the Python environment that you have installed (e.g. `Py27`, `Py36`, etc.); run the following command to activate the Python version you want
```
source activate *
```
4. Run the following command to deactivate the current Python version (NOT uninstall)
```
source deactivate
```
