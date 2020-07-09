Summary
=======

*italic*
**bold**
`python <www.python.org>`_
``*``

Índice
======

* :ref:`genindex`
* :ref:`modindex`

Summary of project

Section 1
---------

Stuff in section

Section 1.1
~~~~~~~~~~~

Stuff in subsection

This creates a new conda environment containing the module.

.. attention::

        ``Lorem ipsum`` dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua.

.. caution::

        ``Lorem ipsum`` dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua.

.. danger::

        ``Lorem ipsum`` dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua.

.. error::

        ``Lorem ipsum`` dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua.

.. hint::

        ``Lorem ipsum`` dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua.


.. important::

        ``Lorem ipsum`` dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua.


.. note::

        ``Lorem ipsum`` dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua.


.. tip::

        ``Lorem ipsum`` dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua.


.. warning::

        ``Lorem ipsum`` dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua.


Instalación
============

rinohtype supports Python 3.3 and up. Use pip_ to install the latest version
of rinohtype and its dependencies::

    pip install rinohtype

If you plan on using rinohtype as an alternative to LaTeX, you will want to
install Sphinx_ as well::

    pip install Sphinx

.. _Sphinx: http://sphinx-doc.org

Code block
----------
.. code-block:: python

    from virtualenv import cli_run

    cli_run(["venv"])

Dependencies
------------

For parsing reStructuredText and CommonMark documents, rinohtype depends on
docutils_ and recommonmark_ respectively. pip takes care of these requirements
automatically when you install rinohtype.

If you want to include images other than PDF, PNG or JPEG, you need to install
Pillow_ additionally.

.. _pip: https://pip.pypa.io
.. _docutils: http://docutils.sourceforge.net/index.html
.. _recommonmark: https://recommonmark.readthedocs.io
.. _Pillow: http://python-pillow.github.io

Copiado de la página de Sphinx
------------------------------

copiado desde acá link_sphinx_

.. _link_sphinx: https://www.sphinx-doc.org/en/1.8/usage/restructuredtext/directives.html#directive-code-block

Example:

Ejemplo de code-block, buscar explicación de los parametros caption y name

.. code-block:: python
    :linenos:
    
    def some_function():
        interesting = False
        print 'This line is highlighted.'
        print 'This one is not...'
        print '...but this one is.'
