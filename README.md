# DeepSketchHashing
![alt tag](https://github.com/ymcidence/DeepSketchHashing/blob/master/DSH.jpg)
-----------------------------------------------------------------------------
This is the repository for reproducing some key results for our paper

- [**Deep Sketch Hashing: Fast Free-hand Sketch-Based Image Retrieval**](https://arxiv.org/abs/1703.05605.pdf)
- by Li Liu, Fumin Shen, Yuming Shen, Xianglong Liu and Ling Shao

to be presented on [CVPR 2017](http://cvpr2017.thecvf.com/) spotlight section. This work focuses on fast sketch-based image retrieval (SBIR) using binary codes.

## Prerequisites
To produce the binary codes described in the paper, one needs to install [Caffe](http://caffe.berkeleyvision.org/) beforehand.
The mid-level Sketch-Token representation is required for training the model. The codes can be found [here](https://github.com/gitlim/SketchTokens). Please refer to the following papers for more details.
- [J. M. Saavedra, J. M. Barrios, and S. Orand. Sketch based image retrieval using learned keyshapes (lks). in BMVC 2015.](http://www.bmva.org/bmvc/2015/papers/paper164/paper164.pdf)
- [Lim, Joseph J., C. Lawrence Zitnick, and Piotr Dollár. Sketch tokens: A learned mid-level representation for contour and object detection. in CVPR. 2013.](http://people.csail.mit.edu/lim/paper/SketchTokens_cvpr13.pdf)

## Models
We provide several pretrained models on two datasets with their respective deploy files. You may try to use any of these models to produce hash code for image-sketch matching.

### [Sketchy Dataset](http://sketchy.eye.gatech.edu/) (Extended)
- [64 bits](https://drive.google.com/file/d/0B2U-hnwRkpRrWkhiZEExNi1Hd1U/view?usp=sharing)
- [128 bits](https://drive.google.com/file/d/0B2U-hnwRkpRrLTh2YnlvcnVORDA/view?usp=sharing)

### [TU Berlin Sketch Dataset](http://cybertron.cg.tu-berlin.de/eitz/projects/classifysketch/)
- [64 bits](https://drive.google.com/file/d/0B2U-hnwRkpRraVlzRl9Qd2M2emM/view?usp=sharing)
- [128 bits](https://drive.google.com/file/d/0B2U-hnwRkpRrNi1YN1dPTXJDaW8/view?usp=sharing)
