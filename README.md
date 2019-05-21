# Markov State Modelling Workshop May 2019


### Aimed at: 
Anyone interested in learning how to use Markov state models to analyse molecular simulations.


### Requirements:  

- Basic Python knowledge
- Basic Linear algebra
- Basic knowledge of setting up and running molecular simulations 


### Abstract: 
Markov State Models (MSM) are a set of tools to analyse molecular simulation trajectories in order to obtain estimates of long-timescale dynamics and free energies for the system of study. MSMs have been used in the past to study short term dynamics such as side chain rearrangements, to much longer dynamical properties such as protein folding, allostery, or protein-protein association. This workshop will give an introduction to the theory behind MSMs followed by a hands-on session on building an MSM. Essential steps such as clustering the simulation data, estimation of the MSM and validation of the MSM as well as the MSMs physical interpretations will be covered. We will be using pyEMMA as the software framework throughout the workshop.

### Training Material
The training material consists of several notebooks:   
[01_IO\_Clustering.ipynb](Tutorial/01_IO_clustering.ipynb)   
[02\_estimation\_validation.ipynb](Tutorial/02_estimation_validation.ipynb)   
[03\_msm\_analysis.ipynb](Tutorial/03_msm_analysis.ipynb)   
[04\_pcca\_tpt.ipynb](Tutorial/04_pcca_tpt.ipynb)



For Installation instructions please see the pyemma website: [pyemma.org](pyemma.org)

### Further reading
If you want to get started with some more background reading for MSMs these are references are a good starting point:

<a id="cite-msm-jhp"/><sup><a href=#ref-1>[1]</a></sup>Prinz, Jan-Hendrik and Wu, Hao and Sarich, Marco and Keller, Bettina and Senne, Martin and Held, Martin and Chodera, John D. and Schütte, Christof and Noé, Frank. 2011. _Markov models of molecular kinetics: Generation and validation_. [URL](http://scitation.aip.org/content/aip/journal/jcp/134/17/10.1063/1.3565032)

<a id="cite-msm-book"/><sup><a href=#ref-2>[2]</a></sup>Gregory R. Bowman and Vijay S. Pande and Frank Noé. 2014. _An Introduction to Markov State Models and Their Application to Long Timescale Molecular Simulation_. [URL](https://doi.org/10.1007%2F978-94-007-7606-7)

<a id="cite-msm-brooke"/><sup><a href=#ref-3>[3]</a></sup>Brooke E. Husic and Vijay S. Pande. 2018. _Markov State Models: From an Art to a Science_.

And of course the pyemma tutorial manuscript this material is based on:

<a id="MSM_tutorial"/><sup><a href=#ref-3>[4]</a></sup>Wehmeyer et al 2018. _Introduction to Markov state modeling with the PyEMMA software_. [URL](https://www.livecomsjournal.org/section/943-tutorials)


### Contact:

Antonia Mey @ppxasjsm (github.com/ppxasjsm)   
Please raise issues on github with bugs or comments. 


### Licence:
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" title='This work is licensed under a Creative Commons Attribution 4.0 International License.' align="left"/></a>
