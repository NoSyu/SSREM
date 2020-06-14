# Speaker Sensitive Response Evaluation Model

## Overview
This repo provides the implementation of Speaker Sensitive Response Evaluation Model (SSREM).


## Tested Environment
- Python 3.6.3
- Pytorch 1.3


## How to run
In `src` folder, we make bash script file to train and evaluate SSREM.
All arguments for the bash files are passed into argparse in `configs.py`.

- `Run_train.sh`: a bash script file to train SSREM

``
bash Run_train.sh 0 TC SSREM 5000 2000 1e-4
``

- `Run_eval1.sh`: a bash script file to identify the true and false responses

``
bash Run_eval1.sh 0 TC SSREM 5000 ../results/TC/SSREM/20191209_235959/2000.pkl 4
``
  


## Data
We use Twitter conversation corpus: https://www.aclweb.org/anthology/D19-1202/
Please contact to the authors of the paper to get the corpus.


## Supports
Please write questions in this repos issues section if you meet any problems.

## Reference
- TBD
