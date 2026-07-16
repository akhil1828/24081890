Installation and Running Instructions
Option 1: Run in Google Colab
Upload the notebook to Google Colab.
Open the notebook.
Run the installation cell:
!pip install pandas numpy matplotlib scipy statsmodels scikit-learn tensorflow joblib requests
Restart the runtime only when Colab requests it.
Run all notebook cells from top to bottom:
Runtime → Run all
Keep internet access enabled because the electricity and weather datasets are downloaded automatically.
Allow the SARIMA parameter search and LSTM training cells to complete before running the final comparison section.
Option 2: Run on a Local Computer

Python 3 and Jupyter Notebook or JupyterLab are required.

Install the necessary packages:

pip install pandas numpy matplotlib scipy statsmodels scikit-learn tensorflow joblib requests jupyter

Start Jupyter Notebook:

jupyter notebook

Open the project notebook and run the cells sequentially from the first cell to the last.

Required Libraries
pandas
numpy
matplotlib
scipy
statsmodels
scikit-learn
tensorflow
joblib
requests
jupyter
Important Running Notes
Run the notebook cells in their original order.
Do not run modelling cells before completing data preparation.
Internet access is required for downloading electricity and temperature data.
The SARIMA search tests 147 parameter combinations and may take several minutes.
LSTM training time depends on the available processor or GPU.
Confirm that the final output states that all models predict the same 104 test dates.
Generated figures, model files and result tables are saved automatically in their respective output folders.
