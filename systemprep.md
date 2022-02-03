# System Preparation

First of all, download and install the Visual Studio Code from [this link](https://code.visualstudio.com/Download). After the installation, the next step is to launch the Visual Studio Code application. Type “jupyter notebook” in the extension search box. Select the result (Jupyter) and click on the Install button displayed in the middle of the screen.

Once the installation is finished, the Jupyter Notebook is in your VS Code.

## Install Visual Studio Code and the Python Extension

Before experiencing Python, install the Python extension for VS Code from the Visual Studio Marketplace. The Python extension is named Python and it's published by Microsoft. 

## Install a Python interpreter

Along with the Python extension, you need to install a Python interpreter.

#### Windows

Install Python from python.org. Typically, use the Download Python button that appears first on the page to download the latest version.

#### macOS

The system install of Python on macOS is not supported. Instead, an installation through Homebrew is recommended. To install Python using Homebrew on macOS use  at the Terminal prompt.

    brew install python3

For a detail explanation please visit this link to the [Microsoft Visual Studi Code's website](https://code.visualstudio.com/docs/python/python-tutorial).

## Install Jupyter Notebook (JupyterLab)

Install JupyterLab with pip:

    pip install jupyterlab

Once installed, launch JupyterLab with:

    jupyter-lab


## Creating a New Jupyter Notebook File

To create a new Jupyter Notebook file, press Ctrl-Shift-P (Shift-Cmd-P for macOS) to bring the Command Palette up. Type “Jup” and you will see a list of options. Select “Jupyter Notebook: Create New Blank Notebook”

A new blank Jupyter Notebook will be created.

## Running Python Code

Finally, test the Jupyter Notebook by writing some Python statements. Press Ctrl-Enter to run the current cell, or press Shift-Enter to run the current cell and move to the next cell (if the current cell is the last cell in the notebook, a new cell will be created).
