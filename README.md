
# [Pytorch] Super-Resolution CNN

MPS GPGPU Version of SRCNN model 

CUDA/CPU version: https://github.com/Nhat-Thanh/SRCNN-Pytorch


## Contents
- [Train](#train)

## Train
You run this command to begin the training:
```
python train.py  --steps=300000                    \
                 --architecture="915"       \
                 --batch_size=128           \
                 --save-best-only=0         \
                 --save-every=1000          \
                 --save-log=0               \
                 --ckpt-dir="checkpoint/x2" 
```
- **--save-best-only**: if it's equal to **0**, model weights will be saved every **save-every** steps.
- **--save-log**: if it's equal to **1**, **train loss, train metric, validation loss, validation metric** will be saved every **save-every** steps.
  
