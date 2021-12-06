Tutorials
=========

Instructions
------------

The tutorials are written as `jupyter notebooks` - browser based Python kernels to run, document, and visualize code (`https://jupyter.org/ <https://jupyter.org/>`_). If you installed Python using Anaconda, it is possible that `jupyter` is already installed (check with :code:`jupyter --version` ). 

#. Install phenopype (see `installation instructions <installation.html>`_) and jupyter notebook (:code:`pip install jupyter notebook`)
#. `Download <https://github.com/phenopype/phenopype-tutorials/archive/refs/heads/main.zip>`_ and unpack the tutorials from github
#. Open a terminal in the unpacked phenopype repository.
#. Start the notebooks with :code:`jupyter notebook` and click on one of the tutorial files.
#. Run the code cell by cell

.. warning::

	Make sure you install jupyter notebook to your specific environment (i.e. activate it first using :code:`conda activate "pp"`. If `jupyter` is not installed in a specific environment, running :code:`jupyter notebook` will fall back on the conda base environment where phenopype may not be installed (this is a common source of confusion).


Tutorials (read-only)
---------------------

These are html / read-only versions of the jupyter notebooks containing the tutorials which are stored under (`https://github.com/phenopype/phenopype-tutorials <https://github.com/phenopype/phenopype-tutorials>`_). To run the notebooks yourself, follow the above instructions.  

.. tip::
	If you want to use the tutorials or `vignettes <https://www.phenopype.org/vignettes>`_ as a blueprint for your own project, simply save them as a Python script from juypter notebook using File > Download as > Python (.py).


.. grid:: 2

	.. grid-item::

		.. card::  Tutorial 1
			:link: tutorial_1_python_intro.html

			A (very) brief python introduction
			
			- Python modules
			- Paths and directories
			- Images in Python
			
		
	.. grid-item::

		.. card::  Tutorial 2
			:link: tutorial_2_phenopype_images.html

			Interacting with images in phenopype
			
			- Window control
			- Opening images
			- Creating masks


.. grid:: 2

	.. grid-item::

		.. card::  Tutorial 3
			:link: tutorial_3_phenopype_workflows.html

			Image analysis workflow
			
			- Low- vs High-throughput
			- YAML-syntax

	.. grid-item::

		.. card::  Tutorial 4
			:link: tutorial_4_managing_projects.html

			Setting up and managing projects	
			
			- Project directories
			- Saving and loading projects
			- Adding images and configs
			- collecting results
		
		
.. grid:: 2

	.. grid-item::

		.. card::  Tutorial 5
			:link: tutorial_5_references.html

			Creating and detecting a reference
			
			- Project wide size references
			
	.. grid-item::

		.. card::  Tutorial 6
			:link: tutorial_6_video_analysis.html
			
			Video analysis
			
			- Motion tracker class
			- Tracking methods
			
		
.. toctree::
	:hidden:

	tutorial_1_python_intro
	tutorial_2_phenopype_images
	tutorial_3_phenopype_workflows
	tutorial_4_managing_projects
	tutorial_5_references
	tutorial_6_video_analysis
