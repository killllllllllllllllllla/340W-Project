# STHSL

## How to run this code
Make sure that you have python 3.9.7 installed as your environment
Open terminal and open folder --> Example: cd "C:\Users\name\OneDrive\Desktop\STHSL-main"
Then type 
```
python train.py --data NYC --device cpu
```
or for Chicago dataset 
```
train.py --data CHI --device cpu
```
IF YOU GET AN ERROR ABOUT TORCH INSTALL TORCH 
```
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
```
You may have to edit above depending on the computer your running the code on
for test 
```
python test.py --data NYC --checkpoint ./Save/NYC/your_file_names
python test.py --data CHI --checkpoint ./Save/CHI/your_file_name
```

## Environment requirement
The code can be run in the following environments, other version of required packages may also work.
* python==3.9.7
* numpy==1.22.3
* pytorch==1.9.0

