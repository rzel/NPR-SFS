
NPR Shape-From-Shading techniques.
====

Sample implementations of Shape-From-Shading techniques for NPR.

* **Lumo: Illumination for Cel Animation** [Johnston et al. 2002]
    - Normal estimation from silhouettes.
* **Image-Based Material Editing** [Kahn et al. 2006]
    - Normal estimation from illumination.


## Result
*Status*: Under construction.
<!-- ### Lit-Sphere
![Lit-Sphere](LitSphere/results/LitSphere.png) -->

## Installation

*Note*: The program was only tested on **Windows** with **Python2.7**.
**Linux** and **Mac OS** are not officially supported,
but the following instructions might be helpful for installing on those environments.

### Dependencies
Please install the following required python modules.

* **NumPy**
* **SciPy**
* **matplotlib**
* **OpenCV**
* **PyAMG**
* **docopt**

For 64-bit Windows, you can download the binaries from [Unofficial Windows Binaries for Python Extension Packages](http://www.lfd.uci.edu/~gohlke/pythonlibs/).

### Install main modules
You can use pip command for installing main modules.
Please run the following command from the shell.
``` bash
  > pip install git+https://github.com/tody411/NPR-SFS.git
```

## Usage
### Directory Structure
* npr_sfs: main package.
    - methods: SFS main modules.
        - lumo.py: **Lumo** implementation.

## License

The MIT License 2015 (c) tody