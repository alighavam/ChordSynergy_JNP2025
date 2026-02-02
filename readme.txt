Code base for Ghavampour et al. 2025 JNP.

-----------------------------------------------------------------------------
----------------------------- File Descriptions ----------------------------- 
-----------------------------------------------------------------------------
matlab_figures.m: This reproduces the analyses and figures for Experiment 1 (learning all 242 chords) and Experiment 3 (EMG and difficulty modeling). 

python_figures.ipynb: Jupyter notebook to reproduce the analyses and figures for Experiment 2 (learning and generalization).


---------------------------------------------------------------------------------------
----------------------------- How to Run the MATLAB Code? -----------------------------
---------------------------------------------------------------------------------------
In summary you need to 1) create a project directory and place datasets into appropriate folders, 2) addpath the functions I used.

1) The recommended directory creation is: 
Clone the repo in ~/Desktop/Projects/
Then:
mkdir ~/Desktop/Projects/ChordSynergy_JNP2025/analysis
mkdir ~/Desktop/Projects/ChordSynergy_JNP2025/data
mkdir ~/Desktop/Projects/ChordSynergy_JNP2025/figures

Then place these files into /analysis:
////efc1_all.tsv
////efc1_chord.tsv
efc1_subj04_raw.tsv (you can select any subjects to plot but I randomly selected this guy)
efc1_subj04_mov.mat (same here)


2) Add the ~/Desktop/Projects/ChordSynergy_JNP2025/functions to your MATLAB path. These are my functions. 
Clone and addpath the MATLAB dataframe toolbox: https://github.com/jdiedrichsen/dataframe/tree/master


---------------------------------------------------------------------------------------
----------------------------- How to Run the Python Code? -----------------------------
---------------------------------------------------------------------------------------
In summary you need to 1) create a project directory and place datasets into appropriate folders, 2) create an environment, install the toolboxes I used.

1) Make a directory just like described above for running the MATLAB code.

Place these files into /analysis:
//////////experiment2_all.csv
//////////experiment2_111_mov.pkl

2) Install the required tools: 'pip install pandas seaborn statsmodels'
















