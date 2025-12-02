# PKLNet
Palm keypoint localization neural network for touchless palmprint recognition
# How to use
## Requirements
- Anaconda 
- PyThorch 1.7
- Python 3.8

## Test PKNet
```shell
cd path/to/PKLNet

# download 'net_params_500.pth' here.

conda activate pklnet # (depends on your python version)

# modify the test folder (`dataset_dir`) path in `test.py`

python test.py
```
> The ROI localization results will be stored at the current folder. (see folder `rst_test`)


```
conda create -n pklnet python=3.8
conda activate pklnet
pip install -r requirements.txt 
```
