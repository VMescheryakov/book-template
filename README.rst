Заготовка документации
======================

Example Project usage
---------------------

This project has a standard Jupyter Book layout which is built by Read the Docs almost the same way that you would build it locally (on your own laptop!).


.. code-block:: console

    # Install required Python dependencies (Sphinx etc.)
    pip install -r docs/requirements.txt

    # Run Jupyter Book
    jupyter-book build docs/
    
    # View the docs with for instance firefox
    firefox docs/_build/index.html


Using the example in your own project
-------------------------------------

If you are new to Read the Docs, you may want to refer to the `Read the Docs User documentation <https://docs.readthedocs.io/>`_.


#. use your existing project repository or create a new repository on GitHub, GitLab, Bitbucket or another host supported by Read the Docs
#. copy ``.readthedocs.yaml`` and the ``docs/`` folder into your project.
#. if you want to have a README on GitHub, create a ``README.rst`` which will be included in ``index.md``.
#. if you *do not* want your README from GitHub included in the docs, edit `ìndex.md`` and remove the ``eval-rst`` block that includes it.
#. if you don't already have a ``.gitignore``, use the one from the project file -- otherwise add these lines::

    /docs/conf.py
    /docs/_build

#. customize all the files, replacing example contents.
#. rebuild the documenation locally to see that it works.
#. *finally*, register your project on Read the Docs, see `Importing Your Documentation <https://docs.readthedocs.io/en/stable/intro/import-guide.html>`_.


Read the Docs Tutorial
----------------------

To get started with Read the Docs, you may also refer to the `Read the Docs Tutorial <https://docs.readthedocs.io/en/stable/tutorial/>`__.
It provides a full walk-through of building an example project similar to the one in this repository.
