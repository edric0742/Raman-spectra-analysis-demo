# Raman-spectra-analysis-demo
This MATLAB code provides tools for pre-processing and experimenting with spectral data, including spectrum visualization, PCA (Principal Component Analysis), and peak ratio extraction. This is a demo version and may still be incomplete, so feedback and suggestions are very welcome.

MATLAB Code Usage Guide

=========================================

1. DATA REQUIREMENTS

The main folder must contain several subfolders.
Each subfolder should include multiple .txt files with two columns: wavenumber and intensity.

2. WORKFLOW

When you run the program, it will ask you to select the main folder containing your data. Then you will go through these steps:

- Data cutting: remove spectral regions that do not contain important information. 

- Grouping data: you can choose which datasets belong to the same group. Group naming can either follow your own custom names or reuse the subfolder names.

After that, you can choose among the following options:

+ Option 2 – visualize data in different spectral forms: raw spectra, baseline-corrected spectra, normalized spectra, or averaged spectra. In normalization, you have three options: z-score, max-min and vector-norm.

+ Option 3 – perform PCA and extract both the score plot and loadings.

+ Option 4 – extract desired peak values and calculate peak ratios.

+ Option 5 – visualize boxplots of the calculated ratios between groups.

3. HOW TO RUN

After downloading, go to Home → Set Path in MATLAB (Home) and add the folder that contains all the .p files. Run the program by executing: Single_spectra in command window

****Caution****
+ Each time you run the program, you will be able to select one option from the menu.
+ To start a different option, run Single_spectra again.
+ Only Option 1 will clear all previous data.

=========================================

If you have any comments or suggestions, please send them to lpduong96@gmail.com.
Your feedback is highly appreciated and will help improve this code.
