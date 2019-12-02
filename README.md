Lectures on scientific computing with Python
============================================

A set of lectures on scientific computing with Python, using IPython notebooks.

To open these notebooks in IPython, download the files to a directory on your computer and from that directory run:

    $ ipython notebook

This will open a new page in your browser with a list of the available notebooks.

Should this error `[TerminalIPythonApp] WARNING | File not found: u'notebook'` pop up, please install Jupyter by following the [instructions](http://jupyter.readthedocs.io/en/latest/install.html) and execute the following command to run the notebook:

    $ jupyter notebook


Online read-only versions
=========================

Use the following links:

* [Lecture-0 Scientific Computing with Python](http://nbviewer.ipython.org/urls/raw.github.com/jrjohansson/scientific-python-lectures/master/Lecture-0-Scientific-Computing-with-Python.ipynb)
* [Lecture-1 Introduction to Python Programming](http://nbviewer.ipython.org/urls/raw.github.com/jrjohansson/scientific-python-lectures/master/Lecture-1-Introduction-to-Python-Programming.ipynb)
* [Lecture-2 Numpy - multidimensional data arrays](http://nbviewer.ipython.org/urls/raw.github.com/jrjohansson/scientific-python-lectures/master/Lecture-2-Numpy.ipynb)
* [Lecture-3 Scipy - Library of scientific algorithms](http://nbviewer.ipython.org/urls/raw.github.com/jrjohansson/scientific-python-lectures/master/Lecture-3-Scipy.ipynb)
* [Lecture-4 Matplotlib - 2D and 3D plotting](http://nbviewer.ipython.org/urls/raw.github.com/jrjohansson/scientific-python-lectures/master/Lecture-4-Matplotlib.ipynb)
* [Lecture-5 Sympy - Symbolic algebra](http://nbviewer.ipython.org/urls/raw.github.com/jrjohansson/scientific-python-lectures/master/Lecture-5-Sympy.ipynb)
* [Lecture-6A C and Fortran integration](http://nbviewer.ipython.org/urls/raw.github.com/jrjohansson/scientific-python-lectures/master/Lecture-6A-Fortran-and-C.ipynb)
* [Lecture-6B HPC](http://nbviewer.ipython.org/urls/raw.github.com/jrjohansson/scientific-python-lectures/master/Lecture-6B-HPC.ipynb)
* [Lecture-7 Revision Control Software](http://nbviewer.ipython.org/urls/raw.github.com/jrjohansson/scientific-python-lectures/master/Lecture-7-Revision-Control-Software.ipynb)

A PDF file containing all the lectures is available here: [Scientific Computing with Python](http://raw.github.com/jrjohansson/scientific-python-lectures/master/Scientific-Computing-with-Python.pdf)


License
=======

This work is licensed under a [Creative Commons Attribution 3.0 Unported License.](http://creativecommons.org/licenses/by/3.0/)


# >>> conda initialize >>>
# !! Contents within this block are managed by 'conda init' !!
__conda_setup="$('/home/pythoncourse/miniconda3/bin/conda' 'shell.bash' 'hook' 2> /dev/null)"
if [ $? -eq 0 ]; then
    eval "$__conda_setup"
else
    if [ -f "/home/pythoncourse/miniconda3/etc/profile.d/conda.sh" ]; then
        . "/home/pythoncourse/miniconda3/etc/profile.d/conda.sh"
    else
        export PATH="/home/pythoncourse/miniconda3/bin:$PATH"
    fi
fi
unset __conda_setup
# <<< conda initialize <<<
