# York-Fisheye-Image-Rectification-Dataset

This dataset provides paired perspective camera images and fisheye camera images as well as the reverse mapping matrix. These images are rendered directly with 3D models via the software [blender](https://www.blender.org/), where the models are created by some artists as listed below. With these models, we create the animation to capture 3D objects from different angles into a sequence of frames with perspective and fisheye cameras, respectively. The focal distance of the perspective camera is set to 16mm and the field of view of the fisheye camera is set to 160 degrees. The resolution of these frames is rendered as 512 pixels. We then save these frames into images with lossless compression and generate the dataset.

| Model        | Artist           | Original file  | Distribution license |
| :-------------: |:-------------:| :-------------:| :-----:|
| Pack of Smokies      | [yd](https://www.blendswap.com/profile/5455)      |   [link](https://www.blendswap.com/blend/24690) | CC-0|
| Chair      | [pujiyanto](https://www.blendswap.com/profile/918426)      |   [link](https://www.blendswap.com/blend/24551) | CC-0|
| Human Skull      | [geoffreymarchal](https://www.blendswap.com/profile/180520)      |   [link](https://www.blendswap.com/blend/23998) | CC-BY-NC|
| Cyber Teddy      | [slimshadow](https://www.blendswap.com/profile/223336)      |   [link](https://www.blendswap.com/blend/22229) | CC-BY-NC-SA |

## Citation
If you want to use this dataset, please cite this paper.
```
@article{lan2020colorglr,
  title={Joint Demosaicking / Rectification of Fisheye Camera Images Using Multi-Color Graph Laplacian Regularization},
  author={Lan, Fengbo and Yang, Cheng and Cheung, Gene and Tan, Jack ZG},
  journal={arXiv preprint arXiv:2006.11636},
  year={2020}
}
```
