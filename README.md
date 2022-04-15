# HappyWhale
My work on the Kaggle Happywhale competition 2022

This code is meant to be run on Kaggle notebooks with direct access to my Kaggle datasets, thus it cannot be run successfully on it's own without being adapted to new datasets.

The way to use the code is like this:
1. Use the happywhale-dataset.ipynb notebook to create the subset for hyperparameter tuning by setting H_PARAMS=True.
2. Perform hyperparameter tuning with the happywhale-training.ipynb notebook.
3. Use the happywhale-dataset.ipynb notebook to create the training dataset by setting H_PARAMS=False.
4. Perform training with the happywhale-training.ipynb notebook.
5. Perform inference with the happywhale-inference.ipynb notebook.
6. Submit the CSV files!
