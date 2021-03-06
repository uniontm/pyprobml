# pyprobml
Python 3 code for the second edition of my book [Machine learning: a probabilistic perspective](http://people.cs.ubc.ca/~murphyk/MLbook/). 
The new book will be split into 2 volumes, "Probabilistic ML: An Introduction" and "Probabilistic ML: Advanced Topics". 
Volume 1 will be released in Spring 2021, volume 2 in Summer 2021.
This is work in progress, so expect rough edges.

## Notebooks

I have created [Jupyter notebooks](https://github.com/probml/pyprobml/tree/master/notebooks) for some of the chapters (more coming later). When you open a notebook, there will be a button at the top that says 'Open in colab'. If you click on this, it will start a virtual machine (VM) instance on Google Cloud Platform (GCP), running [Colab](https://colab.sandbox.google.com/notebooks/welcome.ipynb),  which has most of the libraries you will need (e.g., scikit-learn, tensorflow 2, JAX) pre-installed. Execute the code in the colab to temporally pip-install any remaining libraries. (You can select 'GPU' from the 'Runtime' menu at the top of Colab to make things run faster, but you will get logged out automatically if your session is idle for too long.) Alternatively, you can run these notebooks locally on your desktop in Jupyter, but then you will have to install the packages yourself (see instructions below).

<!--
* [Introduction](https://nbviewer.jupyter.org/github/probml/pyprobml/blob/master/notebooks/intro/intro.ipynb?flush_cache=true)
-->

## Scripts

Many of the figures in the book are generated by these  [scripts](scripts). To execute a script, cd (change directory) to the scripts folder, and then type 'python foo.py'. You can also run each script from inside a Python IDE (like Spyder).
Many of the scripts create plots, which are saved to ../figures.

To run the scripts, we assume you have installed the packages listed in the [requirements.txt](https://github.com/probml/pyprobml/scripts/requirements.txt) file.
Most of these are bundled with [anaconda](https://www.anaconda.com/distribution/). 

## Table of contents

Preliminary version, 2020-12-01.

### Volume 1
<img src="https://github.com/probml/pyprobml/blob/master/book/pml1-toc-201201.png">

### Volume 2
<img src="https://github.com/probml/pyprobml/blob/master/book/pml2-toc-201201.png">


 





