# Audio Classification using LSTM

Classification of Urban Sound Audio Dataset using LSTM-based model.

### Requirements
```
- pytorch==1.0.1
- scipy==1.2.0
- torchvision==0.2.1
- pandas==0.24.1
- numpy==1.14.3
- torchaudio==0.2
- librosa==0.6.3
- pydub==0.23.1
```
### Steps to follow for testing on your Test Data

- Create a folder named data/test in the current directory which will contain all the <b>'.wav'</b> files that are to be tested.
- 

- Run the following commands:
```
python preprocess.py
python eval.py
```

- A csv file named <b>'test_predictions.csv'</b> will be generated in the current directory containing all the test files along with their corresponding predicted labels. 
