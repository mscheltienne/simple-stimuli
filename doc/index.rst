.. include:: ./links.inc

Simple-stimuli
==============

.. toctree::
   :hidden:

   api/index
   cli
   generated/tutorials/index
   changes/index

Simple-stimuli is a Python package for delivery of simple auditory and visuals
stimuli which does not require `PsychoPy`_\ :footcite:p:`peirce_psychopy2_2019,
peirce_generating_2008,peirce_psychopypsychophysics_2007`. Instead, it uses
``opencv-python`` for visual stimuli and ``sounddevice`` for auditory stimuli.
For complex paradigm and use cases, `PsychoPy`_\
:footcite:p:`peirce_psychopy2_2019,peirce_generating_2008,
peirce_psychopypsychophysics_2007` and its builder
should be preferred.

Install
-------

Simple-stimuli is available on `PyPI <project pypi_>`_ and
on `conda-forge <project conda_>`_.

.. tab-set::

    .. tab-item:: PyPI

        .. code-block:: bash

            pip install stimuli

    .. tab-item:: Conda

        .. code-block:: bash

            conda install -c conda-forge stimuli

    .. tab-item:: Source

        .. code-block:: bash

            pip install git+https://github.com/mscheltienne/simple-stimuli

Citation
--------

If you use this package, please cite using the information in
`CITATION.cff <project citation_>`_.

.. tab-set::

    .. tab-item:: APA

        .. code-block::
            :name: APA

            Scheltienne, M. simple-stimuli [Computer software]. https://github.com/mscheltienne/simple-stimuli

    .. tab-item:: BibTex

        .. code-block::
            :name: BibTex

            @software{Scheltienne_simple-stimuli,
              author = {Scheltienne, Mathieu},
              license = {MIT},
              title = {{simple-stimuli}},
              url = {https://github.com/mscheltienne/simple-stimuli}
            }

License
-------

``simple-stimuli`` is licensed under the `MIT license`_.
A full copy of the license can be found `on GitHub <project license_>`_.

References
----------

.. footbibliography::
