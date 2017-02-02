

.. _sphx_glr_auto_examples_plot_legend.py:


=============================
Generating a legend
=============================

An example of how to use the `legend` kwarg to generate a legend.




.. image:: /auto_examples/images/sphx_glr_plot_legend_001.png
    :align: center





.. code-block:: python


    # Code source: Andrew Heusser
    # License: MIT

    import hypertools as hyp
    import scipy.io as sio
    import numpy as np

    data=sio.loadmat('sample_data/weights.mat')
    w=[i for i in data['weights'][0][0:2]]

    hyp.plot(w,'o', legend=['Group A', 'Group B'])

**Total running time of the script:** ( 0 minutes  0.088 seconds)



.. container:: sphx-glr-footer


  .. container:: sphx-glr-download

     :download:`Download Python source code: plot_legend.py <plot_legend.py>`



  .. container:: sphx-glr-download

     :download:`Download Jupyter notebook: plot_legend.ipynb <plot_legend.ipynb>`

.. rst-class:: sphx-glr-signature

    `Generated by Sphinx-Gallery <http://sphinx-gallery.readthedocs.io>`_