# HMDO: Markerless multi-view hand manipulation capture with deformable objects

This repository contains the HMDO (Hand Manipulation with Deformable Objects) dataset for the paper "HMDO: Markerless multi-view hand manipulation capture with deformable objects".

\[[Paper](https://arxiv.org/pdf/2301.07652.pdf)\]



## CONTENT
The HMDO dataset is the markerless deformable interaction dataset, which records the interactive motions of the hands and 12 deformable objects. Its main focus is the non-rigid contact deformation of interacting objects.

```
# object = 12
# cam = 10
# frame = 21600
```

[HMDO Dataset](https://pan.baidu.com/s/1Px-pf2gdTPLjRI0NEGv4TQ?pwd=uinc)  


The HMDO dataset layout is described as below.
```
${HMDO}
|-- sequence
|   |-- img
|   |   |-- cam00 ~ cam09
|   |-- hand_mesh
|   |   |-- hand_mesh.ply
|   |-- object_mesh
|   |   |-- object_mesh.ply
|   |-- hand_annotation
|   |   |-- hand_annotation.txt
|   |-- object_annotation
|   |   |-- object_annotation.txt
|   |-- calib.yml
|-- template_models
```

hand_annotation.txt contains information about hand parameters (scale, trans, mano_fullpose). \
object_annotation.txt contains information about object 6DoF pose. \
calib.yml contains information about cam_extrinsic and cam_intrinsic parameters for 10 cameras.



## CONTACT
For questions about the dataset please contact Yangang Wang (yangangwang@seu.edu.cn) and Wei Xie (xiewei.xw@outlook.com).



## LICENCE
This dataset is provided for research purposes only. Any commercial use is prohibited. If you use the dataset or parts of it in your research, please cite the following paper.

```
@article{xie2023hmdo,
  title={HMDO: Markerless multi-view hand manipulation capture with deformable objects},
  author={Xie, Wei and Yu, Zhipeng and Zhao, Zimeng and Zuo, Binghui and Wang, Yangang},
  journal={Graphical Models},
  volume={127},
  pages={101178},
  year={2023},
  publisher={Elsevier}
}
```
