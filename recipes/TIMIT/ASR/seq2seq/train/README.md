# TIMIT ASR with seq2seq models.
This folder contains the scripts to train a seq2seq RNNN-based system using TIMIT.


# How to run
python train.py train/train.yaml

# Results

| Release | hyperparams file | Val. PER | Test PER | Model link | GPUs |
|:-------------:|:---------------------------:| -----:| -----:| --------:| :-----------:|
| 20-05-22 | train.yaml |  --.- | --.- | Not Available | 1xV100 32GB |

# Training Time
About 2 min and 50 sec for each epoch with a  TESLA V100.
