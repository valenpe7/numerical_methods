[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/valenpe7/numerical_methods/HEAD?filepath=tutorials)

# 12NME1 - Numerical Methods

This repository contains auxiliary study materials for undergraduate course <b>12NME1 - Numerical Methods</b> lectured at the Faculty of Nuclear Sciences and Physical Engineering, Czech Technical University in Prague (https://petrvalenta.eu/teaching/numerical_methods/).

### About the study materials:

The study materials currently consist of only the implementation of selected numerical methods and algorithms (without comments). For closer info, you should attend the tutorials. The methods are written in Python 3, and organized into a collection of Jupyter notebooks. In addition, they rely on several Python packages:
- numpy (mainly for data structures)
- scipy (for several numerical algorithms)
- matplotlib (for visualization)

Although all these packages can be installed one-by-one, I recommend to obtain them by installing Anaconda.

### What is Anaconda and how to install it:

Anaconda is a Python distribution for scientific computing. It includes Jupyter and dozens of the most popular Python packages for scientific computing, including numpy, scipy and matplotlib. 

To install Anaconda, 
1. open https://www.anaconda.com/products/individual with your web browser
2. download the suitable Anaconda installer for Windows/MacOS/Linux (you will find them at the bottom of the web page)
3. install Anaconda using all of the defaults for installation except make sure to check that the Anaconda distribution is the default Python

### How to obtain the notebooks:

All the notebooks are stored in this GitHub repository under the `tutorials` directory. You may either download all the notebooks as a .zip archive by selecting "Code" and then "Download ZIP", or use `git`:

1. Clone the repository: ``` $> git clone https://github.com/valenpe7/numerical_methods.git ```
2. Pull in new changes: ``` $> git pull ```

### How to launch the notebooks:

After you have installed Anaconda on your computer and obtained the notebooks, you are ready to run the notebook server. You can start the notebook server from the command line (Terminal on MacOS/Linux, Anaconda Prompt on Windows) by running:
```
$> jupyter notebook
```
This will print some information about the notebook server in your terminal, including the URL of the web application (by default, `http://localhost:8888`), and open your default web browser to this URL. When Jupyter opens in your browser, you will see the "Notebook Dashboard", which will show a list of the notebooks, files, and subdirectories in the directory where the notebook server was started. Navigate to the `tutorials` directory and click on the selected notebook.

Alternatively, if you do not have installed Anaconda, you may launch the notebooks on-line using

* **Jupyter NBViwever** (non-interactive): https://nbviewer.jupyter.org/github/valenpe7/numerical_methods/blob/master/index.ipynb
* **Binder** (interactive): https://mybinder.org/v2/gh/valenpe7/numerical_methods/HEAD?filepath=tutorials

### Useful links (in Czech):

- Guidelines to lectures and seminars: http://kfe.fjfi.cvut.cz/~limpouch/numet/NMECvic.pdf
- Outline of lecture: http://kfe.fjfi.cvut.cz/~limpouch/numet/sylnum.html
- Transparencies of lectures: http://kfe.fjfi.cvut.cz/~limpouch/numet/lecnum.html
- References to numerical methods: http://kfe.fjfi.cvut.cz/~limpouch/numet/refnum.html
- Further study materials: http://kfe.fjfi.cvut.cz/~vachal/edu/nme/


The study materials are evolving quickly. Therefore, if you find any mistake, please submit an **[issue](https://github.com/valenpe7/numerical_methods/issues)** to this GitHub project repository.
