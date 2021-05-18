# About this course

This website contains auxiliary study materials for undergraduate course <b>12NME1 - Numerical Methods</b> lectured at the [Faculty of Nuclear Sciences and Physical Engineering](https://www.fjfi.cvut.cz/en/), [Czech Technical University in Prague](https://www.cvut.cz/en).

The study materials currently contain only the implementation of selected numerical methods and a very brief description. For closer details, you should attend the tutorials. The methods are written in [Python 3](https://www.python.org/) and organized into a collection of [Jupyter](https://jupyter.org/) notebooks. In addition, they rely on several Python packages:

- [numpy](https://numpy.org/) (for data structures)
- [scipy](https://www.scipy.org/) (for numerical algorithms)
- [matplotlib](https://matplotlib.org/) (for visualization)

There are two ways how to work with the study materials, online or offline.

## Run the notebooks online

If you want to work with the study materials online using your web browser, click the {fa}`rocket` icon on the top-right corner of the tutorial page and select the `Binder` button. By clicking the `Binder` button, you will be redirected to a live version of the page. This lets you quickly interact with the content in a traditional coding interface.

To make the content interactive without leaving the tutorial page, you can select the `Live Code` button. When clicked, each code cell on the page will be converted into an interactive cell that can be edited.

## Run the notebooks offline

If you do not want to work with the study materials online, you may download each tutorial notebook to your computer by clicking the {fa}`download` icon on the top-right corner of the page and select the `.ipynb` button. To open the downloaded file, you need to have installed all the necessary packages specified above. Although all the packages can be installed one-by-one, I recommend to obtain them by installing [Anaconda](https://www.anaconda.com/).

### What is Anaconda and how to install it

Anaconda is a Python distribution for scientific computing. It includes Jupyter and dozens of the most popular Python packages for scientific computing, including numpy, scipy and matplotlib. 

To install Anaconda, 
1. open https://www.anaconda.com/products/individual with your web browser
2. download the suitable Anaconda installer for Windows/MacOS/Linux (you will find them at the bottom of the web page)
3. install Anaconda using all of the defaults for installation except make sure to check that the Anaconda distribution is the default Python

### How to launch the notebooks

After you have installed Anaconda on your computer and obtained the notebooks, you are ready to run the notebook server. You can start the notebook server from the command line (Terminal on MacOS/Linux, Anaconda Prompt on Windows) by running:
```
$> jupyter notebook
```
This will print some information about the notebook server in your terminal, including the URL of the web application (by default, `http://localhost:8888`), and open your default web browser to this URL. When Jupyter opens in your browser, you will see the "Notebook Dashboard", which will show a list of the notebooks, files, and subdirectories in the directory where the notebook server was started. By navigating and clicking on the downloaded `.ipynb` file you will launch the notebook.

The study materials are evolving quickly. Therefore, if you find any mistake, please submit an [issue](https://github.com/valenpe7/numerical_methods/issues) to the GitHub project [repository](https://github.com/valenpe7/numerical_methods).