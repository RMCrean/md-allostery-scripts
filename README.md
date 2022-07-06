# md-allostery-scripts
Random collection of scripts I have made that can be used to support various types of allostery analysis via graph theory.


Below, the contents of each folder will be explained. 


### Folder 1: WISP 

Here you will find an example .r script to run [Weighted Implementation of Suboptimal Paths (WISP)](https://pubs.acs.org/doi/10.1021/ct4008603) with [Bio3d](http://thegrantlab.org/bio3d). This requires you to have installed the "bio3d" and "igraph" libraries for R ahead of time. 

Following this you can use the provided python script "gen_pymol_visuals.py" to generate a visualisation script that is compatible with PyMOL. 

The inputs and results generated are also provided for reproducibility/so you can see how to format your inputs for the WISP calculation. 

Please note that it is possible to get Bio3D to generate the correlation and distance matrix you need if you have not yet generated it like I have here. [You can click here for a tutorial that covers how to do that](http://thegrantlab.org/bio3d/articles/online/cna_vignette/cna_vignette.spin.html).


