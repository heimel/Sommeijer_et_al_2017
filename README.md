# Data for Sommeijer et al. 2017 Nature Neuroscience

The matlab data in this repository can be used to remake the panels of Figures 1b,c and 2b-f of Sommeijer et al. (Nature Neuroscience, 2017). To make the figures, perform the following steps:

1. Download the mat-files to a folder named 'Sommeijer_et_al_2017'. 
2. Download the InVivoTools software repository from https://github.com/heimel/InVivoTools
3. Run the script `load_invivotools.m` in the root folder of InVivoTools in Matlab
4. If the folder 'Sommeijer_et_al_2017' was created on the Desktop, then proceed to step 6.
5. Edit processparams_local.m and add the line `params.databasepath_localroot = 'XXX'`  
where XXX should be the name of the parent folder in of the Sommeijer_et_al_2017 folder
6. Type `experiment('sommeijer_et_al_2017')` on the matlab-prompt.
7. Run the script `graph_db` to open a gui which with the figures 1b,1d and 2b-f can be created. By clicking on [<] and [>], you can go to the different figures. By clicking on [Compute] the selected figure will be created. Check the online wiki-site https://github.com/heimel/InVivoTools/wiki for more information on how to use InVivoTools. 
8. Run the script `experiment_db` to open the database with the individual test runs. The response and timecourse fields contain the measurement from the imaging blocks. By clicking on [Results] a figure of the data is shown. 

Other figures in the manuscript involving spiking data use a more complex set of analysis scripts. Code and data available on request.