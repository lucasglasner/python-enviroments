### Python conda enviroments for hydrology/hydraulics coding

The idea of this repository is to store some python enviroments with the necesary packages for the hydrology/hydraulics professional.

The core of each enviroment is to have all the required python tools for:

* Time series analysis
* GIS-vector analysis
* GIS-raster analysis
* Structured and non-structured grid analysis.
* Machine learning and AI
* Tools for CFD and climate models.

Further work on this project might include tools in other programming languages and command line programs. Like google earth engine, SAGA-GIS, GRASS-GIS, etc.

The python enviroment was originally created on linux OS so there might be problems when trying to install the packages on a Windows machine. A windows OS enviroment will soon be uploaded.

---

How to install a new python enviroment from scratch?

```text
conda create -n mispaquetesfavoritos
```

How to export an already created enviroment?

```text
conda activate mispaquetesfavoritos
conda env export > mispaquetesfavoritos.yml
```

How to install an enviroment from a shared .yml file?

```text
conda env create -f mispaquetesfavoritos.yml
```

For more details on how to handle conda enviroments go for this:

[https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#]()

[https://mamba.readthedocs.io/en/latest/]()
