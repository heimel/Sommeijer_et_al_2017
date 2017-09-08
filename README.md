# Data for Sommeijer et al. 2017 Nature Neuroscience

The matlab data in this repository can be used to remake the panels for Figures 1 and 2 of Sommeijer et al. (Nature Neuroscience, 2017). To make the figures, performt the following steps:

1. Download the mat-files to a folder named 'Sommeijer_et_al_2017'. 
2. Download the InVivoTools software repository from https://github.com/heimel/InVivoTools
3. Run the script `load_invivotools.m` in the root folder of InVivoTools in Matlab
4. If the folder 'Sommeijer_et_al_2017' was created on the Desktop, then proceed to step 6.
5. Edit processparams_local.m and add the line `params.databasepath_localroot = 'XXX'`  
where XXX should be the name of the parent folder in of the Sommeijer_et_al_2017 folder
6. Type `experiment('sommeijer_et_al_2017')` on the matlab-prompt.
7. Run the script `graph_db` to open a gui which with the figures can be created. Check the online wiki-site https://github.com/heimel/InVivoTools/wiki for more information on how to use InVivoTools.

