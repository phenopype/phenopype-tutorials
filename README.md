phenopype tutorials
===================

Instructions
------------

(From https://phenopype.org/docs/tutorials)

The tutorials are written as `jupyter notebooks` - browser based Python kernels to run, document, and visualize code (`https://jupyter.org/ <https://jupyter.org/>`_). If you installed Python using Anaconda, it is possible that `jupyter` is already installed (check with `jupyter --version` - you should see something like `notebook : 6.4.11` in the list that appears). If no list appears, your need to install jupyter notebook first.

1. Install phenopype (see `installation instructions <installation.html>`_) and jupyter notebook (`pip install jupyter notebook`)
2. `Download <https://github.com/phenopype/phenopype-tutorials/archive/refs/heads/main.zip>`_ and unpack the tutorials from github
3. Open a terminal in the unpacked phenopype repository - don't forget to activate your conda environment (see warning below).
4. Start the notebooks with `jupyter notebook` and click on one of the tutorial files.
5. Run the code cell by cell inside the browser window (Shift + Enter to run cell and advance).

You may get a warning when you open jupyter in the browser that the page is not secure - this is fine, the browser simply does not recognize that you are "browsing" the notebooks on your local computer where no ssl / https security certificate is issued, as it should be when browsing the open web.

Make sure you install jupyter notebook to your specific environment (i.e. activate it first using `conda activate pp`. If it is not installed in a specific environment, running `jupyter notebook` will fall back on the conda base environment where phenopype may not be installed (this is a common source of confusion).
