# ShinyaTakiyama2024JB

This repository is for sharing Matlab scripts used in our article:

**Shinya M and Takiyama K**  
"Guidelines for balancing the number of trials and the number of subjects to ensure the statistical power to detect variability – Implication for gait studies"  
**J Biomech.** (2024) 165:111995. [10.1016/j.jbiomech.2024.111995](https://doi.org/10.1016/j.jbiomech.2024.111995)


---
### Matlab LiveScript
- demo_independentSamplesDesign.mlx
- demo_pairedSampleDesign.mlx

Detailed instructions are included in the LiveScript files.

[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=masahiroshinya/ShinyaTakiyama2024JB)


---
### How to run the simulation (post-hoc power analysis)

- Make sure that you have a Mathworks account. You can run the code with your free account. 
- Click the 'Open in Matlab Online' icon.
- Import the repository into your Matlab online.
  ![image](https://github.com/masahiroshinya/ShinyaTakiyama2024JB/assets/16458591/46507b6a-4bce-4113-ae77-483e37f1cf42)

- Input values of your research plan for the simulation:
  - Expected difference in variance
  - Number of trials
  - Number of subjects
    ![image](https://github.com/masahiroshinya/ShinyaTakiyama2024JB/assets/16458591/9ddfe3f6-4d9f-4a08-bb1d-3f68d8ab7fcf)
  The screenshot is for independent-samples-design (i.e., comparison between different groups of subjects)

- Run the code and you will get the statistical power to detect a significant difference given the research plan.
  ![image](https://github.com/masahiroshinya/ShinyaTakiyama2024JB/assets/16458591/a2fe0e8c-2d5e-4318-ba94-3856dd7be23c)
The results suggest 88% of statistical power with the given parameters.

