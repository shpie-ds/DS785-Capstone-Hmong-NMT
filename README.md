# DS785-Capstone-Hmong-NMT
This repository contains all the data for my capstone project which attempted to create an NMT off of a small parallel dataset of Hmong-English health-related text.

The capstone used CoCalc Jupyter Notebooks and the Hugging Face Ecosystem to recall two base models and fine-tune them on the dataset.

## Dataset
The dataset can be found under this name: shpie/Hmong-to-Eng-4k

## Models
The first model is: shpie/t5-base-en2vi-finetuned-Hmong-to-English
The second model is: shpie/t5-base-en2vi-finetuned-English-to-Hmong
The third model is: shpie/byt5-small-finetuned-Hmong-to-English
The fourth model is: shpie/byt5-small-finetuned-English-to-Hmong

## Tokenizer
The tokenizer for the first and second model is: shpie/Hmong_Tokenizer_t5_base
