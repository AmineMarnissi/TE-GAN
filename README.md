# <a href="https://ieeexplore.ieee.org/document/9412331"> Thermal Image Enhancement using Generative Adversarial Network for Pedestrian Detection </a>
## This implementation for our ICPR 2020 paper, training YOLOv3 on KAIST dataset with ....

### This implementation was expanded from our previous work which was the Best Student Paper Honorable Mention Award <a href="https://github.com/mrkieumy/YOLOv3_PyTorch"> "Domain Adaptation for Privacy-Preserving Pedestrian Detection in Thermal Imagery" </a> . 


### The short introduction of paper 
[![Video detection](examples/firstslide.jpg)](https://www.youtube.com/watch?v=e5yBbxVOcUY&ab_channel=ArtificialIntelligence "Click to play on Youtube.com")

# TE-GAN
Thermal Image Enhancement using Generative Adversarial Network for Pedestrian Detection
![architecture](https://user-images.githubusercontent.com/35928931/96371909-7a3aae80-1164-11eb-9356-7b888abae9cb.PNG)

### Results on KAIST dataset:
#### Our reported result on ICPR 2021 paper:

Qualitative results of our proposed architecture TE-GAN:
![Result](enhancement_results.gif)
 
 
 Results of the Proposed Te-Gan Architecture:

|     | HE | CLAHE | TE-GAN
| --- | --- | --- | --- |
|PSNR | 7.81 | 11.92 | 13.92 |
|SSIM | 0.34 | 0.37 | 0.50 |

 Results of Pedestrian Detection:

|Testing condions| Metri | Without enhancement | With enhancement
| --- | --- | --- | --- |
|Day | mAP| 0.61 | 0.63 |
|    | LAMR| 0.41 | 0.40 |
|Night | mAP| 0.66 | 0.73 |
|    | LAMR| 0.26 | 0.20 |
|All | mAP| 0.62 | 0.65 |
|    | LAMR| 0.45 | 0.43 |



## Citation
We really hope this repository is useful for you. Please cite our paper as
```
@INPROCEEDINGS{9412331,
  author={Marnissi, Mohamed Amine and Fradi, Hajer and Sahbani, Anis and Ben Amara, Najoua Essoukri},
  booktitle={2020 25th International Conference on Pattern Recognition (ICPR)}, 
  title={Thermal Image Enhancement using Generative Adversarial Network for Pedestrian Detection}, 
  year={2021}
  }

```

If you have any comment or question about this repository, please leave it in Issues.

Other contribution, please contact me by email: mohamed.amine.marnissi@gmail.com.

Thank you so much for your interest in our work.
