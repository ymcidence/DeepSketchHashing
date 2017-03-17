# DeepSketchHashing
![alt tag](https://github.com/ymcidence/DeepSketchHashing/blob/master/DSH.jpg)
-----------------------------------------------------------------------------
This is the repository for reproducing some key results for our paper

- [**Deep Sketch Hashing: Fast Free-hand Sketch-Based Image Retrieval**](https://128.84.21.199/pdf/1703.05605.pdf)
- by Li Liu, Fumin Shen, Yuming Shen, Xianglong Liu and Ling Shao

to be presented on [CVPR 2017](http://cvpr2017.thecvf.com/) spotlight section. This work focuses on fast sketch-based image retrieval (SBIR) using binary codes.

## Prerequisites
To produce the binary codes described in the paper, one needs to install [Caffe](http://caffe.berkeleyvision.org/) beforehand.

## Models
We provide several pretrained models on two datasets with their respective deploy files. You may try to use any of these models to produce hash code for image-sketch matching.

### [Sketchy Dataset](http://sketchy.eye.gatech.edu/) (Extended)
- [64 bits](https://drive.google.com/file/d/0B2U-hnwRkpRrWkhiZEExNi1Hd1U/view?usp=sharing)
- [128 bits](https://drive.google.com/file/d/0B2U-hnwRkpRrLTh2YnlvcnVORDA/view?usp=sharing)

### [TU Berlin Sketch Dataset](http://cybertron.cg.tu-berlin.de/eitz/projects/classifysketch/)
- [64 bits](https://drive.google.com/file/d/0B2U-hnwRkpRraVlzRl9Qd2M2emM/view?usp=sharing)
- [128 bits](https://drive.google.com/file/d/0B2U-hnwRkpRrNi1YN1dPTXJDaW8/view?usp=sharing)
