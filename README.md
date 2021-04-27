# Particle-Based-COVID-19-Simulator
## Requirements:
1. OS Windows/Linux/Mac.
2. MATLAB R2019/R2020. 

## COVID-19 Vaccination Strategies Considering Hesitancy Using Particle-Based Epidemic Simulation 

Link to the paper: will be posted later 
 

### How to use?
- To calibrate the model, use **main_v2.m** script. This file contains the parameters' values we used to calibrate the model for province of Lecco, Italy. For more information please refer to the papers listed below. Then, you can use the calibrated model to simulate different vaccination strategies. You can also
download the calibrated model, used in the paper, for the province of Lecco from [here](https://drive.google.com/drive/folders/1JbNz1FaX1_lCMfWsKwQ-ZWPr47z7v6eA?usp=sharing). 
- We added a vaccine hesitancy status to the particle model to exclude certain randomly selected vector of particles that are assined to be vaccine hesitant from the vaccination.
- To simulate effective immunization cases (random vaccination/age based vaccination) considering hesitancy, use **hesitancy_effective_vaccination.m** script.

# Note:
If you use this code in your research, please cite the following papers:
```
@ARTICLE{9372866,
  author={A. {Kuzdeuov} and A. {Karabay} and D. {Baimukashev} and B. {Ibragimov} and H. A. {Varol}},
  journal={IEEE Open Journal of Engineering in Medicine and Biology}, 
  title={A Particle-Based COVID-19 Simulator With Contact Tracing and Testing}, 
  year={2021},
  volume={2},
  number={},
  pages={111-117},
  doi={10.1109/OJEMB.2021.3064506}}
```
```
@article {Karabay2021.03.28.21254468,
	author = {Karabay, Aknur and Kuzdeuov, Askat and Lewis, Michael and Varol, Atakan Huseyin},
	title = {A Vaccination Simulator for COVID-19: Effective and Sterilizing Immunization Cases.},
	elocation-id = {2021.03.28.21254468},
	year = {2021},
	doi = {10.1101/2021.03.28.21254468},
	publisher = {Cold Spring Harbor Laboratory Press},
	URL = {https://www.medrxiv.org/content/early/2021/04/04/2021.03.28.21254468},
	eprint = {https://www.medrxiv.org/content/early/2021/04/04/2021.03.28.21254468.full.pdf},
	journal = {medRxiv}}
```

