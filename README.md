# Cooperative Mobile Brickwork

This repository provides datastructures, tools and methods for assembly information modeling and robotic bricklaying.

### Requirements

* [Rhinoceros 7 / Grasshopper](https://www.rhino3d.com/download/)
* [Anaconda Python](https://www.anaconda.com/distribution/?gclid=CjwKCAjwo9rtBRAdEiwA_WXcFoyH8v3m-gVC55J6YzR0HpgB8R-PwM-FClIIR1bIPYZXsBtbPRfJ8xoC6HsQAvD_BwE)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Github Desktop](https://desktop.github.com/)

### Dependencies

* [COMPAS](https://compas-dev.github.io/)

### 1. Setting up the Anaconda environment with COMPAS

Execute the commands below in Anaconda Prompt:
	
    (base) conda config --add channels conda-forge

#### Windows
    (base) conda create -n comobrick compas --yes
    (base) conda activate comobrick

#### Mac
    (base) conda create -n comobrick compas python.app --yes
    (base) conda activate comobrick
    
#### Verify Installation

    (comobrick) python -m compas

    
    Yay! COMPAS is installed correctly!

#### Install on Rhino

    (comobrick) python -m compas_rhino.install -v 7.0

### 2. Cloning the Course Repository

Create a workspace directory:

    C:\Users\YOUR_USERNAME\workspace\projects

Then open Github Desktop and clone the [Cooperative Mobile Brickwork repository](https://github.com/augmentedfabricationlab/cooperative_mobile_brickwork) repository into your projects folder. Then install the repo within your environment (in editable mode):

    (comobrick) pip install -e your_filepath_to_cooperative_mobile_brickwork
    (comobrick) python -m compas_rhino.install -p cooperative_mobile_brickwork -v 7.0

**Voilà! You can now go to VS Code, Rhino or Grasshopper to run the example files!**
