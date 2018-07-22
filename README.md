# lstm-time-series-prediction

### Description
The program I developed is a deep learning time series predictor that use a recurrent neural network architecture tailored by long-short term memory cells. The dataset used to train this model represents the monthly milk production in pounds per cow from January 1962 to December 1975 Cryer (1986). This datasetcan be accessed on the following website: [Monthly milk production](https://datamarket.com/data/set/22ox/monthly-milk-production-pounds-per-cow-jan-62-dec-75#!ds=22ox&display=line)

##### List of Features

1) Time
2) Pounds per cow


### Dependencies
You can use `pip` or `conda` to install the dependencies:
- tensorflow
- matplotlib
- jupyter
- pandas
- seaborn
- scikit-learn

### Usage
If you want to try this program, download this repo and launch jupyter to run it on your machine. You can also check it out clicking on this link: [LSTM Time Series Prediction](https://nbviewer.jupyter.org/github/igerardoh/lstm-time-series-prediction/blob/master/lstm-time-series-prediction.ipynb)

### - - - TODO  - - -
- LOAD AND VISUALIZE THE RAW DATA
   - ~~Load the dataset and show statistic summary~~
   - ~~Visualize the data~~

- DATA PREPROCESSING
   - Apply standarization to features
   - Apply one-hot encoding to labels
   - Split data into training and testing sets

- MODEL ARCHITECTURE
   - Define network parameters
   - Define network structure
   - Define learning rate with different decaying methods
   - Set up cost, optimizer, and accuracy function with different configurations
   - Define model execution
   - Visualize evolution of training and testing accuracy through epoch iteration
   - Visualize evolution of learning rate

- OTHERS [OPTIONAL
   - Add log and summary writer
   - Add Tensorboard visualization
   - Add checkpoints for model restoration
   - ~~Update README file~~