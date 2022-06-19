# RIGA: Covert and Robust White-Box Watermarking of Deep Neural Networks

This work is accepted by WebConf 2021 (formerly known as WWW). Paper preprint is available at https://arxiv.org/pdf/1910.14268.pdf. 


## Requirements (not too important as long as you can run)
tensorflow==1.9.0  
Keras==2.0.8  
numpy

## celebA dataset:
Please download from this website, and unzip in CELEBA dir.
https://www.kaggle.com/datasets/ashishjangra27/gender-recognition-200k-images-celeba/download

## Example Transcript
`python main.py dataset_name wm_type save_name`
where `dataset_name` could be mnist, celebA, twitter
`wm_type` could be bits or img.
