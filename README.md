# CUED Finite Element Methods (3D7) Lab

This is the laboratory coursework activity for the Finite Element Course
(3D7). The activity is contained in a Jupyter notebook and uses the open
source [FEniCSx](https://fenicsproject.org/) libraies.

Running the coursework notebook in Colab is recommended. Google does
very occasionally make changes to Colab that can break the required
libraries. In this case the lab can be undertaken using
[Codespaces](https://github.com/codespaces). You can locally on
macOS or Linux.


## Colab (recommended)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/garth-wells/CUED-3D7-Lab)

Cambridge users should use their University credentials (CRSid) to log
in.

> Be sure to use "Copy to Drive" to keep a copy of your notebook.

Google does sometimes makes changes


## Codespaces

[![Create a new Codespace](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=595727051)

You can return to your Codespace at https://github.com/codespaces.
Codespaces core hours per month are limited, so it is helpful to stop
running Codespaces at https://github.com/codespaces when you have
finished working. You can restart the Codespace at any time.


## Locally (macOS and Linux only)

The DOLFINx library used in this lab can be installed using [conda](https://conda.io).

```shell
conda create -n fenicsx-env
conda activate fenicsx-env
conda install -c conda-forge fenics-dolfinx=0.7.3 jupyterlab matplotlib mpich python-gmsh pyvista
```


## Author

These notebooks are developed by Garth N. Wells (<gnw20@cam.ac.uk>).