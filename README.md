
## Introduction

WQChartPy is an open source python package developed for graphical diagrams 
of water geochemistry data. Utilizing the commonly used Excel XLSX or 
CSV (Comma Separated Value) as the input data format, WQChartPy can produce 
twelve diagrams including not only the traditional Piper diagram, 
Stiff diagram, Durov diagram and Schoeller diagram, but also the recently 
proposed new diagrams such as the rectangle Piper, colored Piper and HFE-D 
that has not implemented in previous software. 

This is the first release of WQChartPy. As a Python-based cross platform 
program, WQChartPy works on Windows, MacOS X and GNU/Linux. We provided a 
self-contained Jupyter notebook file to illustrate how to use WQChartPy. 
Users with a little Python experience can do the whole process from data to 
the graphical diagrams. Buidling on the oldest and most popular Python 
plotting library Matplotlib, the figures generated by WQChartPy can be saved 
as portable network graphics (PNG), scalable vector graphics (SVG) or portable 
document format (PDF). WQChartPy is an open-source project and any
assistance is welcomed. Please email the development team if you want to
contribute.


## Installation

WQChartPy requires **Python** 3.7 (or higher). We recommend using [Anaconda](https://www.anaconda.com/) on Windows or Linux platforms. 

The easiest way to install is via `pip`:

To install WQChartPy type:

    pip install wqchartpy

To update WQChartPy type:

    pip install wqchartpy --upgrade

To uninstall WQChartPy type:

    pip uninstall wqchartpy
    
Another way is to manually install WQChartPy with `setup.py`. Preliminary steps to take:

    1. Download the package and extract it into a local directory

    2. cd into the root directory where setup.py is located using an Anaconda Prompt

    3. Enter: python setup.py install
    
## Requirements:

- [NumPy](https://www.numpy.org)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://www.scipy.org/scipylib)
- [SciPy](https://salib.readthedocs.io/en/latest/)
    
## Getting started with the package

We recommend to start by executing the workflow scripts provided in the examples folder. 

## License

WQChartPy is distributed under the MIT License. See the [LICENSE](https://github.com/jyangfsu/WQChartPy/LICENSE) file for details.

Copyright (c) 2021 Jing Yang and Ming Ye.

## Contributing to WQChartPy

Users are welcome to submit bug reports, feature requests, and code contributions to this project through GitHub or mail to us at mye@fsu.edu.
