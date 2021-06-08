# BrainFD
The available implement the calculations of Fractal dimension, Lacunarity, rmse, y intercept. The files (scripts, datasets plots) for the final analysis are included in the svm_data rar.

-boxplots.py file          as used to create the boxplots that are shown in the paper
-convert_mgz_to_npz.sh     converts mgz to nii
-create_npz.py             it converts nii files to npz and reduces the size of volume

-fd3D_brain_structure.py   performs the calculations to estimate Df, PΛ, y intercept, rmse , volume of a given brain region
first argument -segmented_volume -number_of_label(0 stands for unknown,1 for Left-Cerebral-Cortex etc.....) -other_parameters_for_naming_the_outputs 

-labels41_vxm.csv          is the file with the lables of vxm (1st column) and freesurfer (2nd column)
