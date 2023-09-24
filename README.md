# DML-Calibration-Heston-Model

We applied the Differential Machine Learning (DML) technique to price vanilla European options (i.e. the calibration instruments) when the underlying asset follows a Heston model and then calibrated the model using the trained network. 

The paper can be accessed here https://lnkd.in/dSXgxtR4



<!-- This repository contains the code I have implemented to this end. You will find:
* Three Jupyter notebooks intended to be opened in a Google Colab environment:
    1. ”DataGeneration.ipynb” file contains the implementation of the Heston pricer, the different differentials of the normalised forward put price w.r.t inputs as well as the generator used to build the datasets utilised to train, validate, and test the neural networks.
    2. ”DifferentialNeuralNetworks.ipynb” file presents how to apply the DML technique to price European put options when the underlying asset follows a Heston model. I also introduced different regularisation techniques and applied them notably in the case of the DML. I compared their performance in reducing overfitting and improving the generalisation error. The DML performance is also compared to the classical Deep Learning (DL) (without differentiation) one in the case of Feed-Forward Neural Networks. I showed that the DML outperforms the DL.
    3. ”Calibration.ipynb” presents how DML is used to reduce Heston calibration’s computation time dramatically and compares traditional calibration to the Differential Neural Network (DNN) based one.

    The files imported into the Google Colab environment are in data_generation/, hyperparam_tuning_res/ and calibration_data/ folders.
    
* A data_generation/ folder contains two .csv files containing the generated synthetic data.
* A calibration_data/ folder contains three .csv files used to calibrate the Heston model on the market data.
* A hyperparam_tuning_res/folder contains two .csv files displaying the results of the hyperparameter tuning.
* A DML_results/ folder contains .pdf files illustrating the results obtained in ”DifferentialNeuralNetworks.ipynb” notebook.
* A Calib_Results/ folder contains .csv and .pdf files representing the results of the calibration process. -->