# Mask-Agnostic Posterior Sampling MRI via Conditional GANs with Guided Reconstruction [[paper]](https://openreview.net/forum?id=AopY31LYgO)
## Setup
See ```docs/setup.md``` for basic environment setup instructions.

## Reproducing our Results
### MRI
See ```docs/mri.md``` for instructions on how to setup and reproduce our MRI results.

## Questions and Concerns
If you have any questions, or run into any issues, don't hesitate to reach out at bendel.8@osu.edu.

## References
This repository contains code from the following works, which should be cited:

```
@article{zbontar2018fastmri,
  title={fastMRI: An open dataset and benchmarks for accelerated MRI},
  author={Zbontar, Jure and Knoll, Florian and Sriram, Anuroop and Murrell, Tullie and Huang, Zhengnan and Muckley, Matthew J and Defazio, Aaron and Stern, Ruben and Johnson, Patricia and Bruno, Mary and others},
  journal={arXiv preprint arXiv:1811.08839},
  year={2018}
}

@article{devries2019evaluation,
  title={On the evaluation of conditional GANs},
  author={DeVries, Terrance and Romero, Adriana and Pineda, Luis and Taylor, Graham W and Drozdzal, Michal},
  journal={arXiv preprint arXiv:1907.08175},
  year={2019}
}

@inproceedings{Karras2020ada,
  title={Training Generative Adversarial Networks with Limited Data},
  author={Tero Karras and Miika Aittala and Janne Hellsten and Samuli Laine and Jaakko Lehtinen and Timo Aila},
  booktitle={Proc. NeurIPS},
  year={2020}
}

@inproceedings{zhao2021comodgan,
  title={Large Scale Image Completion via Co-Modulated Generative Adversarial Networks},
  author={Zhao, Shengyu and Cui, Jonathan and Sheng, Yilun and Dong, Yue and Liang, Xiao and Chang, Eric I and Xu, Yan},
  booktitle={International Conference on Learning Representations (ICLR)},
  year={2021}
}

@misc{zeng2022github,
    howpublished = {Downloaded from \url{https://github.com/zengxianyu/co-mod-gan-pytorch}},
    month = sep,
    author={Yu Zeng},
    title = {co-mod-gan-pytorch},
    year = 2022
}
```

## Citation
If you find this code helpful, please cite our paper:
```
@journal{Bendel:NIPSW:23,
  author = {Bendel, Matthew and Ahmad, Rizwan and Schniter, Philip},
  title = {Mask-Agnostic Posterior Sampling MRI via Conditional GANs with Guided Reconstruction},
  year = {2023},
  journal={NeurIPS 2023 Deep Inverse Workshop}
}
```