# Quasar-Task

# Requirements:
1. Software: Anaconda
2. Interpreter: Python
3. Libraries: pandas, plotly, pathlib

# Jupiter Notebook Setup
Pre-Requisites:
1. pip install pandas
2. pip install plotly
3. pip install pathlib.

# Current Features
1. ECG Mode channels are converted from µV to mV.
2. Created buttons to view custom plots or specifically related to EEG, ECG, CM or all.
3. Zoom In/Out.
4. Export results.
5. Range slider.

# Future Features
1. Channel overlay mode – view selected EEG channels in the same subplot for easier comparison (e.g., Fz vs Cz).
2. Dynamic filtering – apply bandpass filters (alpha, beta, theta bands) for EEG or low/high-pass filters for ECG.
3. Aggregations - apply aggregation functions like sum, avg, min, max to all the channels of different mode to maintain stats.
4. Frequency view – toggle between time-domain plots and frequency analysis (FFT/PSD)
5. Web app version – wrap the notebook into a Plotly Dash or Streamlit app so users can interact in a browser.
6. Database/vector storage – save processed features into a database (MongoDB, SQLite, ChromaDB) for fast retrieval or AI analysis.
