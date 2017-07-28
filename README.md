# Network Evaluation Tools

Network Evaluation Tools is a Python 2.7 package with corresponding examples for evaluating a network's ability to group a given node set in network proximity. This package was developed as a part of the work done in [citation](link). 

## Installing NBS
### Version and Dendencies
Currently, pyNBS requires Python 2.7 - Python 2.7.13. Note that pyNBS may not work with Python 3.0+.
pyNBS requires: 
  - Argparse>=1.1
  - NetworkX>=1.11
  - Numba>=0.32.0
  - Numpy>=1.11.0
  - Matplotlib>=1.5.1
  - Pandas>=0.19.0
  - Requests>=2.13.0
  - Scipy>=0.17.0
  - Scikit-learn>=0.17.1

Note:
- In Pandas v0.20.0+, the ```.ix```indexer has been deprecated. There may be warning regarding this issue, yet the function still works.

### Installation
1. Clone the repository 
2. cd to new respository
3. Execute following command:  
```python setup.py install```

## Network analysis
1. If the network needs to be normalized to a particular naming scheme:<br>
A Jupyter Notebook describing now each network analyzed in the original Huang et al paper can be found in the ```Network_Processing``` folder.<br>
2. There are two ways to execute the NBS code:<br>
	1. From __Jupyter Notebook__. <br>
	```OV_run_pyNBS.ipynb``` and ```UT_run_pyNBS.ipynb```are 2 Jyputer Notebooks that use Ovarian cancer and Uterine cancer data same as [Nature Methods Hofree et al 2013 paper](https://www.nature.com/nmeth/journal/v10/n11/full/nmeth.2651.html) and successfully replicate the paper result using pyNBS. Data can be found in ```data/``` folder. See the ```OV_run_pyNBS.ipynb``` and ```UT_run_pyNBS.ipynb``` jupyter notebook for algorithmic details.
	2. From __command line__.  <br>
	Execute the following command to view parameter/option documentation:<br>
	```Python run_pyNBS.py -h``` <br>
	Run ```Python run_pyNBS.py``` with desired parameters and options in documentation.

## Issues
Please feel free to post issues/bug reports. Questions can be sent to jkh013@ucsd.edu



