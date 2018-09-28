# DeepChemStable
DeepChemStable: chemical stability prediction using attention-based graph convolution network

## Environment
Python 3.6.3
Tensorflow 1.1.0
RDkit 2018.03.4
autograd 1.2
numpy 1.14.2
pandas 0.23.4

## Model
The trained model weights are stored in `fingerprint_variables.bin`, `prediction_variables.bin`. </br>
Use the `predict.py` to predict. </br>
The predictions are saved in the file `results.csv`. </br>

## Usage
`>python predict.py *yourfilepath* *amount*` </br>
Examples: `>python predict.py test.csv 5` </br>

Data file format: </br>
datafile should be CSV file. The header must be "substance_id, smiles, label" </br>
