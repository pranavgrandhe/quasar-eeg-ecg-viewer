# EEG µV + ECG mV Interactive Viewer

This repository contains my solution for the QUASAR Coding Screener – Second Round.
It loads EEG/ECG data from `EEG and ECG data_02_raw.csv` and generates an interactive Plotly figure with dual y-axes.

## Files
- eeg_ecg_viewer.ipynb : full notebook with all code blocks
- requirements.txt : dependencies (pandas, plotly>=6.1.1, kaleido)
- EEG_ECG_dual_axis_plot.png : optional screenshot of the figure output

## How to Run
1. Clone or download this repository:
   git clone https://github.com/<your-username>/eeg-ecg-viewer.git
   cd eeg-ecg-viewer

2. Install dependencies:
   pip install -r requirements.txt

3. Place the data file `EEG and ECG data_02_raw.csv` in the project root.

4. Start Jupyter and run all cells:
   jupyter notebook eeg_ecg_viewer.ipynb

The notebook outputs an interactive dual-axis graph with:
- EEG channels (µV) on the left y-axis
- ECG + CM channels (mV) on the right y-axis
- Range slider, zoom/pan, and a dropdown menu to filter channel groups.

