# ECG 3-Lead to 12-Lead Conversion

This project contains code and data for training a simple LSTM model to predict 12-lead ECG signals from 3-lead input data.

The dataset is provided in `MUSE_20180111_155633_99000.csv`. The file uses a UTF-8 byte order mark (BOM) which must be handled when reading the CSV.

Run the notebook `ECG 3 to 12.ipynb` to train the model. Ensure you have Python with pandas, NumPy, TensorFlow and scikit-learn installed.
