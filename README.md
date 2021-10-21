# RCT-Random-Consistency-Training
Welcome to RCT-Random consistency training! This is the official implementation of RCT.


## Introduction
***
RCT is a semi-supervised training secheme for Sound Event Detection (SED). But we believe it has a more generalized
usage for other applications!

Since the code is constructed for SED, we build RCT based on the baseline model for DCASE 2021 challenge. Please refer
to [[1]](https://github.com/turpaultn/DESED) and [[2]](https://github.com/DCASE-REPO/DESED_task) for more details. 

Here, we will only give a lite introduction of the baseline model.
<div  align="center">    
<image src="/imgs/rct_structure.PNG"  width="500" alt="The structure of RCT" />
</div>

## Training
***
The training/validation data is obtained from the DCSAE2021 task4 [DESED dataset](https://github.com/turpaultn/DESED).
The downloading of the dataset is quite complicated, no all data is available for the accesses. So, your testing result might
be different with an incomplete validation dataset.

To train the model, please first get the baseline architecture of [DCASE2021 task 4](https://github.com/DCASE-REPO/DESED_task)
by:
```git clone git@github.com:DCASE-REPO/DESED_task.git
```
Don't forget to configure your environment as their requirements.

After complete the above setup, you could add the codes of this repo to the baseline repo.

```git clone git@github.com:Audio-WestlakeU/RCT-Random-Consistency-Training.git
```