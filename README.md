# An interactive beat-pattern analysis of spermatozoa

This repository is Cambridge FertiliTEAM's entry to <a href="https://infernetwork.wixsite.com/infer/hackathon" target="_blank">**inFer GW4 Network Hackathon: "Fertility: In Vitro, In Silico, In Clinico"**</a>.

## <span style="color:blue">GOAL: Create an interactive and user-friendly platform that allows researchers to reproduce the analyses and figures presented in the manuscript. Ensure that the platform facilitates easy exploration and understanding of the research findings.</span>



## Table of Contents

- [Solution](#solution)
- [Background](#background)
- [The GUI](#the-gui)
- [Team](#team)

- ---
## Solution
We have designed MATLAB live scripts that: (i) reproduce the data published in the manuscript titled, "Computer-assisted beat-pattern analysis and the flagellar waveforms of bovine spermatozoa", authored by Benjamin J. Walker, Shiva Phuyal, Kenta Ishimoto, Chih-Kuan Tung, and Eamonn A. Gaffney, (ii) allow the user to interact with the data and understand waveform analysis and reconstruction, (iii) perform biophysical modelling of spermatozoa swimming on existing data and visualize trajectories of various sperm cells.

The MATLAB live scripts are: (i) interactive_manuscript.mlx, (ii) explore_waveforms.mlx and (iii) explore_swimming.mlx.

Although the Live Scripts were primarily designed for researchers in the field of IVF and infertility, the scripts can also be used by the general public to gain a better understanding of the link between sperm motility and infertility.

The project meets the requirements of the hackathon in the following ways:

- **Specific**- We have brought to life the figures of the paper titled "Computer-assisted beat-pattern analysis and the flagellar waveforms of bovine spermatozoa", authored by Benjamin J. Walker, Shiva Phuyal, Kenta Ishimoto, Chih-Kuan Tung, and Eamonn A. Gaffney, providing interactive versions of all figures. These are easy to explore and give the user ample options to study and compare different spermatozoa waveforms.
  
- **Measurable**- In addition to reproducing results from the source manuscript, we conduct further quantitative analyses. We investigate waveform reconstruction, wherein our live script outputs a `score' based on the accuracy of waveforms generated by the user via an interactive interface. We also use the dataset for biophysical modelling of swimming spermatozoa, quantifying their kinematics based on flagellar geometries from the dataset.
    
- **Achievable**- All the scripts included in our submission can run easily on standard laptops available to the public, students and researchers. The accompanying reports make it easy to understand the scientific contents of the manuscript.
    
- **Relevant**- Our submission straddles multiple scientific disciplines--biology, statistics, fluid mechanics--and will help researchers in these fields communicate with each other. By reproducing the results of a scientific journal on an interactive interface, we are making that information more accessible to the research community.
    
- **Timebound**- We have successfully reproduced and explained the manuscript's results. We have gone further and dissected the key features present in each of the figures. We now have a framework which can be used to arbitrary datasets on spermatozoa geometry, hence our work is easily extendable to a wide-range of flagellar beat-pattern analyses.


---
## The GUI

 <!---  
<p align="left">
<img  src="https://github.com/Lucyhenley/CardiffMATHBIO_NERCHackathonTwo_PublicTransport/blob/master/figs/screenshot.png?raw=true" alt="App Screenshot" class = "center" width="1000" height = "500"/>
</p>
--->



The live scripts use a Graphical User Interface (GUI) to allow easy manipulation of input variables. There are sliders for:

* sperm ID;

* timepoint;

* number of modes in waveform reconstruction




## Team

The team is comprised of PhD Students and Postdocs from the Department of Applied Mathematics and Theoretical Physics (DAMTP) at the University of Cambridge. The project was conceived, developed, coded and written up by the group. 

| <a href="https://www.damtp.cam.ac.uk/person/nd519" target="_blank">**Nikhil Desai**</a> | <a href="https://www.maths.cam.ac.uk/person/phh35" target="_blank">**Pyae Hein Htet**</a> | <a href="https://www.maths.cam.ac.uk/person/wl354" target="_blank">**Weida Liao**</a> | <a href="https://www.maths.cam.ac.uk/person/mt599" target="_blank">**Maria Tatulea-Codrean**</a> |
| :---: |:---:| :---:| :---:|
| [![Nikhil Desai](https://avatars1.githubusercontent.com/nikhiid?s=200)](https://github.com/nikhiid)    | [![Pyae Hein Htet](https://avatars1.githubusercontent.com/stevenhtet?s=200)](https://github.com/stevenhtet) | [![Weida Liao](https://avatars1.githubusercontent.com/WeidaLiao?s=200)](https://github.com/WeidaLiao)  | [![Maria Tatulea-Codrean](https://avatars1.githubusercontent.com/MariaTatuleaCodrean?s=200)](https://github.com/MariaTatuleaCodrean)  |
| <a href="https://github.com/nikhiid" target="_blank">`github.com/nikhiid`</a> | <a href="https://github.com/stevenhtet" target="_blank">`github.com/stevenhtet`</a> | <a href="https://github.com/WeidaLiao" target="_blank">`github.com/WeidaLiao`</a> | <a href="https://github.com/MariaTatuleaCodrean" target="_blank">`github.com/MariaTatuleaCodrean`</a> |

