Predicting Ground-Level Scene Layout from Aerial Imagery
========

This code is a TensorFlow implementation of this CVPR 2017 paper: [Predicting Ground-Level Scene Layout from Aerial Imagery](http://openaccess.thecvf.com/content_cvpr_2017/papers/Zhai_Predicting_Ground-Level_Scene_CVPR_2017_paper.pdf).

Dependencies
------------
* Tensorflow r1.1 or higher [Installation Page](https://www.tensorflow.org/versions/r1.1/install/).

Running
------------
Training:
```bash
$ python main.py
```

Deploying:
```bash
$ python main.py --is_training=False
```
Data
------------
This repository only contains example data for training; the full dataset can be requested from [this link]([https://drive.google.com/open?id=0BzvmHzyo_zCAX3I4VG1mWnhmcGc](https://mvrl.cse.wustl.edu/datasets/cvusa/). You would have to edit the dataset path in main.py in order to use it.

