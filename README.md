# PromptScan

This is the public repository for the open-source project **PromptScan**. 

### Requirements
tensorflow，keras    2.6.1
numpy      1.22.4

### Demo
Currently, we are sharing a version of pre-trained model that can be used for four downstream tasks. The model can be called using TensorFlow for detecting phisher, Ponzi, MEV bots and airdrop hunters.

https://drive.google.com/drive/folders/12sopwv0cmZBEruWX5bFA9G-QeUDdaEOG?usp=sharing

you can install the folder under Model, then using

```bash
CUDA_VISIBLE_DEVICES=0 python run_phishing_detection_dnn.py --init_checkpoint=pretrained_demo/model_299534
