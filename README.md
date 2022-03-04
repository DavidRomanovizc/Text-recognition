# Text recognition with PyTorch

## Environment
 [![Python](https://img.shields.io/badge/Python-3.7%2B-9cf?style=flat-square)](https://www.python.org/downloads/)
 [![Python](https://img.shields.io/badge/PyTorch-1.10.1%2B-orange?style=flat-square)](https://pytorch.org/get-started/locally/)
 [![anaconda](https://img.shields.io/badge/Anaconda-green?style=flat-square)](https://www.anaconda.com/)
 [![Jupyter](https://img.shields.io/badge/Jupyter-1.0.0%2B-yellow?style=flat-square)](https://jupyter.org/)
 ![matplotlib](https://img.shields.io/badge/Matplotlib-3.5.1%2B-blue?style=flat-square)
 ![openCv](https://img.shields.io/badge/openCv-4.5.3%2B-red?style=flat-square)

## Implementetion
PyTorch implementation of a Deep Neural Network for text recognition. \
It is based on the:
"An End-to-End Trainable Neural Network for Image-based Sequence Recognition and Its Application to Scene Text Recognition" : https://arxiv.org/abs/1507.05717

![image](https://user-images.githubusercontent.com/72649244/149961073-de3040ee-6650-46e0-9911-d0f8881ca442.png)


## Preparing launch
If you use Google coollaboratory, just download the archive, unzip it and upload it to Google Drive. And don't forget to change the paths
And if you have data in zip file you can use this block code:

```py
import zipfile
!mkdir data
!mkdir data/final_data
!mkdir data/final_data/train
with zipfile.ZipFile('/content/drive/MyDrive/your_path') as zf:
    zf.extractall('your path') # ex. data/final_data/train
```

1. Clone this repository in PyCharm `https://github.com/DavidRomanovizc/Text-recognition.git`
2. Create conda enverimont, download pytorch .etc (When you settings environment, choose Python 3.7)
3. Create folders where you put your data (image, models, prediction .etc)
4. Set conda env in Pycharm
5. And then you can run every cell


## Pretrained Model

| Accuracy     | Loss           | CER |
| :---         |     :---:      |          ---: |
| 0.7778       | 0.04343        | 0.0671        |
