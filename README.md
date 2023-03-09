# CEFM
This is the repo for "CEFM: CLIP Encoded Fusion Model for"Multimodal Humor Recognition on Memes" 

For sentence transformer: Follow steps from https://github.com/UKPLab/sentence-transformers

Instructions
The .py contains the exhaustive set of steps required to be run in sequence.

For installing CLIP

! pip3 install torch==1.7.1{torch_version_suffix} torchvision==0.8.2{torch_version_suffix} -f https://download.pytorch.org/whl/torch_stable.html ftfy regex --user

! wget https://openaipublic.azureedge.net/clip/bpe_simple_vocab_16e6.txt.gz -O bpe_simple_vocab_16e6.txt.gz

HUMEME Datasets (Complete) - Meme Images + Annotations

https://pan.baidu.com/s/1HtQ3UbhM4b6yrTAIvKSKaQ 

code：1823

For initializing dataset and data loader for pytorch

Load the data-set for training and testing as per the requirement of the run.

Entity features: https://drive.google.com/file/d/1KBltp_97CJIOcrxln9VbDfoKxbVQKcVN/view?usp=sharing

ROI features: https://drive.google.com/file/d/1KRAJcTme4tmbuNXLQ72NTfnQf3x2YQT_/view?usp=sharing

ROI + Entity features: https://drive.google.com/file/d/1xeviXtHE46md3usybEO2FIAcRkBmXZN7/view?usp=sharing


For initializing dataset and data loader for pytorch

Load the data-set for training and testing as per the requirement of the run.
Experimental setting
Configurations for the binary/multi-class setting (training/testing/evaluation) has to be considered as per the requirement, code blocks for which are provided and suitably commented out.


setting up dependencies

if CUDA_version == "10.0":
    torch_version_suffix = "+cu100"    
elif CUDA_version == "10.1":
    torch_version_suffix = "+cu101"    
elif CUDA_version == "10.2":
    torch_version_suffix = ""    
else:
    torch_version_suffix = "+cu110"







