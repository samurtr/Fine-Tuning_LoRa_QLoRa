# Fine-Tuning_LoRa_QLoRa


## Goal:
Finetune an existing model from HuggingFace with three different approaches and compare results afterwords
1. Full Finetuning (all parameters of the model are tuned)
2. LoRa (Low Rank Adaption)
3. QLoRa (Quantized LoRa)

## Dataset:
The dataset is from HuggingFace and contains text that are ranked from 1-5

## Training:
Training was done on one NVIDIA L4 GPU

Pretrained model: https://huggingface.co/google-bert/bert-base-cased (~109M parameters)

Dataset: https://huggingface.co/datasets/Yelp/yelp_review_full (~700.000 rows)
