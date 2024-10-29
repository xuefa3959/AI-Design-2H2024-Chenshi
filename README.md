# AI-Design-2H2024-Chenshi
Midterm project for AID-2H2024

using the training method from NanoGpt-kaepathy https://github.com/karpathy/nanoGPT

the model has been pretrained,the model file in /out-shakespeare-char/ckpt.pt

the train datasets in /data/shakespeare_char/train.bin and /data/shakespeare_char/val.bin

the environment requirments in requirements.txt

to train the model , run code 'python train.py config/train_shakespeare_char.py'

to eavl it , run code 'python sample.py --out_dir=out-shakespeare-char',you will get the require sentence more than 10 sentences
