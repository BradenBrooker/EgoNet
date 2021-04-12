[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/exploring-intermediate-representation-for/vehicle-pose-estimation-on-kitti-cars-hard)](https://paperswithcode.com/sota/vehicle-pose-estimation-on-kitti-cars-hard?p=exploring-intermediate-representation-for)
# EgoNet
Official project website for the CVPR 2021 paper "Exploring intermediate representation for monocular vehicle pose estimation"

This repository is under preparation. Inference code and pre-trained models are coming soon for quick deployment. Training code will be released before the main conference.

<p align="center">
  <img src="https://github.com/Nicholasli1995/EgoNet/blob/master/imgs/teaser.jpg"  width="830" height="200" />
</p>

## Performance: AP<sup>BEV</sup>@R<sub>40</sub> on KITTI val set for Car (monocular RGB)

| Method                    | Reference|Easy|Moderate|Hard|
| ------------------------- | ---------------| --------------| --------------| --------------| 
|[M3D-RPN](https://arxiv.org/abs/1907.06038)|ICCV 2019|20.85| 15.62| 11.88|
|[MonoDIS](https://openaccess.thecvf.com/content_ICCV_2019/papers/Simonelli_Disentangling_Monocular_3D_Object_Detection_ICCV_2019_paper.pdf)|ICCV 2019|18.45 |12.58 |10.66|
|[MonoPair](https://arxiv.org/abs/2003.00504)|CVPR 2020|24.12| 18.17| 15.76|
|[D4LCN](https://github.com/dingmyu/D4LCN)|CVPR 2020|31.53 |22.58  |17.87|
|[Kinematic3D](https://arxiv.org/abs/2007.09548)|ECCV 2020|27.83| 19.72| 15.10|
|[GrooMeD-NMS](https://github.com/abhi1kumar/groomed_nms)|CVPR 2021 |27.38|19.75|15.92|
|[MonoDLE](https://github.com/xinzhuma/monodle)|CVPR 2021|24.97| 19.33| 17.01|
|Ours           |CVPR 2021 |**33.60**|**25.38**|**22.80**|

## Performance: AOS@R<sub>40</sub> on KITTI test set for Car (RGB)

| Method                    | Reference|Configuration|Easy|Moderate|Hard|
| ------------------------- | ---------------| --------------| --------------| --------------| --------------| 
|[M3D-RPN](https://arxiv.org/abs/1907.06038)|ICCV 2019|Monocular|88.38 |82.81| 67.08|
|[DSGN](https://github.com/Jia-Research-Lab/DSGN)|CVPR 2020|Stereo|95.42|86.03| 78.27|
|[Disp-RCNN](https://github.com/zju3dv/disprcnn)|CVPR 2020|Stereo |93.02 |	81.70 |	67.16|
|[MonoPair](https://arxiv.org/abs/2003.00504)|CVPR 2020|Monocular|91.65 |86.11 |76.45|
|[D4LCN](https://github.com/dingmyu/D4LCN)|CVPR 2020|Monocular|90.01|82.08| 63.98|
|[Kinematic3D](https://arxiv.org/abs/2007.09548)|ECCV 2020|Monocular|58.33 |	45.50 |	34.81|
|[MonoDLE](https://github.com/xinzhuma/monodle)|CVPR 2021|Monocular|93.46| 90.23| 80.11|
|[Ours](http://www.cvlibs.net/datasets/kitti/eval_object_detail.php?&result=e5233225fd5ef36fa63eb00252d9c00024961f2c)           |CVPR 2021 |Monocular|**96.11**|**91.23**|**80.96**|

## Inference/Deployment
Coming soon.

## Training
To be updated.

## Citation
Please star this repository and cite the following paper in your publications if it helps your research:

    @InProceedings{Li_2021_CVPR,
    author = {Li, Shichao and Yan, Zengqiang and Li, Hongyang and Cheng, Kwang-Ting},
    title = {Exploring intermediate representation for monocular vehicle pose estimation},
    booktitle = {The IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    month = {June},
    year = {2021}
    }

## License
This repository can be used freely for non-commercial purposes. Contact me if you are interested in a commercial license.

Link to the paper:
[Exploring intermediate representation for monocular vehicle pose estimation](https://arxiv.org/abs/2011.08464)

Link to the presentation video:
To be added.
