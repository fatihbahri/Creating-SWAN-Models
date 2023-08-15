# README.md

**This repo contains 2 main directory.**

These are **"pretreatment"** and **"Main Tasks"**

The **"Pretreatment"** section includes the preprocessing of data from the DUCK94 project. These include: 

1. Interpolation and extension of the bottom profiles.

2. Editing the spectrum files into excel files

3. Correction of erroneous spectrum data using the Winsorizing method.

4. Correction of timezone mismatch between tidal data from NOAA and other data


> This section also includes some other operations to facilitate the use of the data.

The second part is the **"Main Task"** section. This section contains the necessary files for the creation and evaluation of the models.

Files in the Main Task section:
1. Creation of models by specifying spectrum, bottom profile, tidal data and other parameters.
2. Running the models with SWAN
3. Creating the necessary commands to change the parameters in the models automatically
4. Reading the model result files and transferring them to excel files
5. Making the necessary arrangements for the models to work correctly
6. Creation of comparison files for easier evaluation of models
and the files used to describe the order in which to run these models.

> All these files can be called and executed from a single local runtime.

_Under **"Main Tasks"** is the **"DATA"** folder, which contains a small part of the data of DUCK94._

_There is also an **"Additional Comparison Tools"** folder under the **"Main Tasks"** section. In this folder there are python notebooks in which additional models can be compared. See the readme.md file in this folder for details._


```python

```
