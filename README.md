# MoebInv notebooks
A collections of notebooks on Lie-Möbius sphere geometry and MoebInv package. We discuss and discover mathematical aspects of the theory using a dedicated software.

[annotated Table of Contents](https://github.com/vvkisil/MoebInv-notebooks/blob/master/Table%20of%20contents.ipynb) as Jupyter notebook.


## Running MoebInv notebooks
The code from these notebooks can be executed at Google CoLab after the installation of MoebInv library by a couple of mouse clicks.

Specifically, open the notebook with [library installation instructions](https://colab.research.google.com/github/vvkisil/MoebInv-notebooks/blob/master/Euclidean_and_Lobachevsky_lines.ipynb#Installing-required-software) and execute a couple of cells in this section. Then you can run all other notebooks until your CoLab session will expire.

Alternatively these notebooks can be executed from  a [CodeOcean capsule](https://codeocean.com/capsule/7952650/tree).

## Introductory examples

+ **Euclidean and Lobachevsky lines** This notebook also show how to make initial software installation 
[View on Github](https://colab.research.google.com/github/vvkisil/MoebInv-notebooks/blob/master/Euclidean_and_Lobachevsky_lines.ipynb) or [Execute on Colab](https://colab.research.google.com/github/vvkisil/MoebInv-notebooks/blob/master/Euclidean_and_Lobachevsky_lines.ipynb).

+ **Nine point theorem**: Some non-trivial illustrations on the celebrated result
[View on
  Github](https://colab.research.google.com/github/vvkisil/MoebInv-notebooks/blob/master/Nine_point_theorem.ipynb)
or  [Execute on CoLab](https://colab.research.google.com/github/vvkisil/MoebInv-notebooks/blob/master/Nine_point_theorem.ipynb).

* **Example of symbolic computations** Analytic proof of a simple geometric statement 
[View on
  Github](https://colab.research.google.com/github/vvkisil/MoebInv-notebooks/blob/master/Example_of_symbolic_computations.ipynb)
or  [Execute on CoLab](https://colab.research.google.com/github/vvkisil/MoebInv-notebooks/blob/master/Example_of_symbolic_computations.ipynb).

## Jupyter and MoebInv-GUI integration
There is a Graphical User Interface (GUI) to the MoebInv library. It allows to create and research geometrical constructions by mouse clicks. You may find a pre-compiled GUI binary distribution for your desktop platform at [SourceForge](https://sourceforge.net/projects/moebinv/files/binary/). 

There is bidirectional integration beetween Jupyter and GUI:

* From Jupyter (or any coding system in C++ or Python) use
``` python
F.save("my-figure-archive.gar")
```
to save GiNaC Gar archive. It can be loaded into GUI (or any other front-end, indeed).
* From GUI select
```
File → Export figure → Export Python script
```
in Main Menu and save the script file. Then it can be executed in the IPython or Jupyter cell.

Furthermore, to use such code as Jupyter notebook I recommend to post-process the generated Python script with [p2j (Python to Jupyter)](https://pypi.org/project/p2j/) utility.

Here is an [Example](https://colab.research.google.com/drive/101nZupZRtDXaF5GRrjOmuMHd5oPOzpL8#scrollTo=MIcFs9KN4J4_) of Python script and Jupyter notebook automatically created from the GUI.
