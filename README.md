The attached files (PDFs and Power Point Presentations) cover various subjects related to magnetic circuit design. A Python program with GUI (Chan_model.py) has been developed to reproduce Chan's model, enabling the simulation of magnetic hysteresis BH-loops in cores with and without a gap. Simulation parameters:
# Hc - coercivity without a gap, A/m
# Hmax - maximum magnetization (+/-) when drawing the BH-loop
# Br - residual induction, Tesla (T)
# Bs - saturation induction, T
# Lm - length of the magnetic core (single loop) without a gap, m
# Lg - length of the gap, m
# S - cross-section of the magnetic core, m^2
For more information on Chan's model, please refer to: https://ieeexplore.ieee.org/document/75630

This model is used for simulating non-linear behaviour of transformers in LTspice: https://www.allaboutcircuits.com/technical-articles/simulating-non-linear-transformers-in-ltspice/ See the attached report "A case study on magnetic cores_All files.pdf".

Output files of Chan_model.py (algorithm with GUI): "BH-loop_data.csv", "Averaged_BH-loop_data.csv", and "BH-loop_parameters.txt". Input parameters from the previous program run are saved in "simulation_log.log" (do not delete this file!) and can be called from GUI.

"A case study on magnetic cores_All files.pdf" is the main report with all necessary files attached.

"Magnetic circuits.ppsx" is a Power Point Slide Show (PPS) on magnetic circuits. It can be seen after downloading.

"Introduction to electrodynamics.ppsx" is a Power Point Slide Show (PPS) on electromagnetic principles for college students. It can be seen after downloading.

The folder "LTspice_Non-linear_Transformer" contains the LTspice simulation file for a non-linear transformer. 
