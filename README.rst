==============================================
CLASS_EOS_FR
==============================================
 Cosmic Linear Anisotropy Solving System 

 With Cosmological Perturbations in f(R) Gravity


**The code CLASS_EOS_FR is an extension of the CLASS code.** 

For download and information on **class**, see http://class-code.net and https://github.com/lesgourg/class_public


(README file adapted from the README_CLASS.rst file.)


Downloading the code
--------------

Go to https://github.com/borisbolliet/class_eos_fr_public


Using the code
--------------

You can use **class_eos_fr_public** freely, provided that in your publications you cite
at least the papers:

`Do cosmological data rule out f(R) with w≠−1? (Battye, Bolliet, Pace, 2017)
<https://arxiv.org/abs/1712.05976>`_.

`CLASS II: Approximation schemes (Blas, Lesgourgues, Tram, 2011)
<http://arxiv.org/abs/1104.2933>`_.


Compiling CLASS_EOS_FR and getting started
--------------------------------------

Move to the code repository

    $ cd class_eos_fr_public

Clean up and Compile

    $ make clean

    $ make

(You may need to do a ‘$ sudo make’.) 

The code **class_eos_fr** runs in parallel, so you need a **gcc** compiler that is not **clang**.   

The previous commands compile both the executable and the python wrapper. 
If you do not want the **classy** python module do ‘$ make class’.

For the python module, you need the prerequisites such as **numpy**, **scipy**
and **Cython** installed on your computer.


Then, run the code with 

    $ ./class explanatory-class-eos.ini


The explanatory files are reference input files, containing and
explaning the use of all possible input parameters.


Python Wrapper and Jupyter Notebooks
--------------------------------------


To use CLASS from python, or ipython notebooks, or from the **montepython** parameter extraction code, you need to compile not only the
code, but also its python wrapper. (This can be done by typing just
'make' instead of 'make class’.)


Support
-------

To get support, please open a new issue on:

https://github.com/borisbolliet/class_eos_fr_public

