Code base for Ghavampour et al. 2025 JNP.

-----------------------------------------------------------------------------
----------------------------- File Descriptions ----------------------------- 
-----------------------------------------------------------------------------
=====================
matlab_figures.m: This reproduces the analyses and figures for Experiment 1 (learning all 242 chords) and Experiment 3 (EMG and difficulty modeling).

How to?
Mount the Diedrichsen CBS server. Set the 'project_path' variable on top of the code to the '/Volumes/Diedrichsen_data$/data/Chord_exp/ChordSynergy_JNP2025'. By default the code is set to this path for a mac computer. Alternatively, create your own directory by copying the 'ChordSynergy_JNP2025/analysis' directory and set the path accordingly.

Also, you need to addpath the diedrichsen dataframe toolbox (https://www.diedrichsenlab.org/toolboxes/matlab_toolboxes.htm)

=====================
python_figures.ipynb: Jupyter notebook to reproduce the analyses and figures for Experiment 2 (learning and generalization).

How to?
By default the code works if diedrichsen is mounted on your mac computer. Otherwise you need to set the path in './utils/config.py'

