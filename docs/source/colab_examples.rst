.. _installation:

Colab Examples
============

`Google Colaboratory <https://colab.google/>` (Colab) is is a cloud-based platform that allows users to write and execute Python codes through a browser. Regardless of the user's operating system, Colab provides Linux computing backends and some free GPU access. 

The following Colab examples are created to provide an install-free experience of AutoDock Vina via Google Colab notebooks, which work in a similar manner to `Jupyter Notebooks <https://jupyter.org/>`, in the pre-configured environment with `Meeko <https://github.com/forlilab/Meeko>` for receptor and ligand preparation, and other modules for pre-processing of protein structures and visualization. 

**Subscription is NOT required to run these Colab examples.** Additionally, the input files for the docking calculations are either directly pulled from open databases or generated from user inputs. With that, one can easily customize the notebooks and reuse the workflow for similar calculations on different biochemical systems. 

Overview
------------------------

Packages and data included: 

Meeko
cctbx
Phenix-project/geostd
py3Dmol

Basic docking
------------------------

`091624_Vina_basic_docking.ipynb <https://colab.research.google.com/drive/1cHSl78lBPUc_J1IZxLgN4GwD_ADmohVU?usp=sharing>`

The **basic docking example** is a rewrite based on the original basic docking example. 

Flexible docking
------

`091624_Vina_flexible_docking.ipynb <https://colab.research.google.com/drive/1cazEckGbvl9huWzpxXpd_Qaj0_NipWcz?usp=sharing>`

The **flexible docking example** is a rewrite based on the original flexible docking example. 


Using AD4SF in Vina
---------------

`091624_Vina_docking_with_AD4SF.ipynb <https://colab.research.google.com/drive/1zoSyID2fSoqGz3Zb1_IatUT2uxZ2mCNZ?usp=sharing>`

The **using AutoDock4 (AD4) scoring function (SF) example** is a rewrite based on the corresponding part of the original basic docking example. 
