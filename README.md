# PKLNet
Palm keypoint localization neural network for touchless palmprint recognition

## Requirements
- Anaconda 
- PyThorch 1.7
- Python 3.8

## Test
```shell
cd path/to/PKLNet
# download 'net_params_500.pth' here.
conda activate pklnet # (depends on your python version)
# modify the test folder (`dataset_dir`) path in `test.py`
python test.py
```

```
conda create -n pklnet python=3.8
conda activate pklnet
pip install -r requirements.txt 
```

TODO ...