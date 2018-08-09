# Gaussian Process Poster for Oh and Austin

* This repository contains source code to produce the figures in:

  Oh, Gunho and P. H. Austin, 2018: Quantifying the Oscillatory Evolution of Simulated Boundary-Layer Cloud Fields Using Gaussian Processes, *15th Conference on Cloud Physics, American Meteorological Society*, Vancouver BC, Canada

* [Poster pdf](loh_austin_amscloud_2018.pdf)

* The poster is split into two Jupyter notebooks

  * [Introduction to gaussian regression](notebooks/gaussian_regression.ipynb)
  
      * [Rendered HTML]()

  * [Cloud size distribution](notebooks/cloud_oscillation.ipynb)
  
      * [Rendered HTML](https://gitcdn.link/repo/phaustin/gaussian_processes_ams_2018/master/notebooks/cloud_oscillation.html)

* Installation

  * Install https://conda.io/miniconda.html, accepting the defaults

  * Download [conda_packages.txt](https://raw.githubusercontent.com/phaustin/gaussian_processes_ams_2018/master/utils/conda_packages.txt) by right-clicking on the link.

  * Start bash shell (osx/linux) or an anaconda shell (windows) and type:

         conda install --file conda_packages.txt

    to get the prerequisite packages

  * If this succeeds, then typing he command:

          python -c 'import numpy;print(numpy.__version__)'
 
     should print:

            1.14.2

     (or possibly a higher version)
