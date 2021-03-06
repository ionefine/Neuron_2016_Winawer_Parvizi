# Neuron_2016_Winawer_Parvizi
Code to reproduce the figures associated with the paper &lt;Winawer &amp; Parvizi (2016) Neuron>

This repository is associated with the publication below.

Winawer and Parvizi (2016). Linking Electrical Stimulation of Human
Primary Visual Cortex, Size of Affected Cortical Area, Neuronal
Responses, and Subjective Experience Neuron. 92(6):1213?1219
http://dx.doi.org/10.1016/j.neuron.2016.11.008

The code downloads the data from the Open Science Framework project page (https://dx.doi.org/10.17605/OSF.IO/PZ42U) and then reproduces 4 main figures in the paper, as well as some supplementary figures.

The code runs in Matlab and was written and tested using Matlab2015b on an Apple computer (OS 10.12.2).

Dependencies:
* curve_fitting_toolbox
* optimization_toolbox
* signal_toolbox
* statistics_toolbox

To use the code, download or clone this github repository, then navigate to the repository in the Matlab command window.
Example usage below:

``` Matlab
 % Navigate to the correct folder and add the paths
 addpath(genpath(pwd))
 
 % Download the data (this only needs to be done once)
 ebs_downloadData();
 
 % Make the figures
 ebs_MakeFigure1(); 
 ebs_MakeFigure2();
 ebs_MakeFigure3();
 ebs_MakeFigure4();
 ```
 
Code (c) Jonathan Winawer

Please direct any comments about the code via the issues page associated with this GitHub repository, or via email to jonathan.winawer@nyu.edu
