2016 ACC paper on constrained attitude control.

Work started at AFRL 2015 Space Scholars.

## To regenerate the figures for publications

You need the matlab code located at:
https://github.com/skulumani/2016_ACC_matlab

### Configuration Error Function visualization:
run log_barrier.m to make the surface plots for the \Psi

Go to commit a4e97e069d475b1760d61db2d46c1157281afe1c to make sure the constants
are setup properly

### Attitude Stabilization without adaptive update law:
run coupled_control_driver.m and then run plot_outputs.m to generate the simulation
plots used in both ACC/IJCAS submission

This is also using commit a4e97e069d475b1760d61db2d46c1157281afe1c

### Attitude Stabilization with adaptive update law:
run coupled_control_driver.m and then run plot_outputs.m or draw_cad to generate
the plots. There's a flag in load_constants to create animations or a video

Go to commit 6f5604a9db17ee67b019dac6daa1807e5ed3c6d5 to ensure the constants 
are setup properly

### Constrained Attitude stabilization experiment:
Run Data_analysis.m to read 20150924_avoid3.txt to generate the experimental results

The repository holding the experimental data is located at
https://github.com/skulumani/2016_ACC_Experiment

The commit is 6f5604a9db17ee67b019dac6daa1807e5ed3c6d5

This calls load_experiment_constants and plot_experiment_constants 

## LICENSE

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Geometric Adaptive Control of Attitude Dynamics on SO(3) with State Inequality Constraints</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://fdcl.seas.gwu.edu" property="cc:attributionName" rel="cc:attributionURL">Shankar Kulumani, Christopher Poole, and Taeyoung Lee</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="http://fdcl.seas.gwu.edu" rel="dct:source">http://fdcl.seas.gwu.edu</a>.<br />Permissions beyond the scope of this license may be available at <a xmlns:cc="http://creativecommons.org/ns#" href="http://fdcl.seas.gwu.edu" rel="cc:morePermissions">http://fdcl.seas.gwu.edu</a>.