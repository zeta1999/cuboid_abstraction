# Learning Adaptive Hierarchical Cuboid Abstractions of 3D Shape Collections

This is the TensorFlow implementation of ["Learning Adaptive Hierarchical Cuboid Abstractions of 3D Shape Collections"](https://isunchy.github.io/projects/cuboid_abstraction.html) by Chun-Yu Sun, Qian-Fang Zou, Xin Tong, Yang Liu, SIGGRAPH Asia 2019. The code is released under the MIT license.

<img src="teaser.png" alt="teaser" width=800px; height=373px;/>

## Setup

Pre-prequisites

        Python == 3.6
        TensorFlow == 1.12

## Experiments


### Data Preparation

Now we provide the Google drive link for downloading the training datasets:

>[Training data](https://drive.google.com/drive/folders/1Uh_-CrOyUVpB5mWkSOY-L-b2kpa9LuTC?usp=sharing)

### Training

To start the training, run

        $ python training_script.py --category class_name

### Test

To test a trained model, run

        $ python iterative_training.py --test_data test_tfrecords --test_iter number_of_shape --ckpt /path/to/snapshots --cache_folder /path/to/save/test_results --test

Now we provide the trained weights for generating the results used in our paper:

>[Weights](https://drive.google.com/drive/folders/1ipixLDU4LejE57R8dnLJFTvGvnkilfv_?usp=sharing)


## Citation

If you use our code for research, please cite our paper:
```
@article{sun2019abstraction,
  title     = {Learning Adaptive Hierarchical Cuboid Abstractions of 3D Shape Collections},
  author    = {Sun, Chunyu and Zou, Qianfang and Tong, Xin and Liu, Yang},
  journal   = {ACM Transactions on Graphics (SIGGRAPH Asia)},
  volume    = {38},
  number    = {6},
  year      = {2019},
  publisher = {ACM}
}
```

## Contact

Please contact us (Chunyu Sun sunchyqd@gmail.com, Yang Liu yangliu@microsoft.com) if you have any problem about our implementation.
