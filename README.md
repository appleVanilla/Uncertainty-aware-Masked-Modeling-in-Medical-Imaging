# Mask-awared-Hard-Patches-Mining-in-Mask-Image-Modeling

The project is still under construction :construction:.

## Data Preparation

### Pretraining Dataset

The publicly accessible **LIDC-IDRI** dataset, comprising lung CT scans of 1,010 patients in DICOM format, was utilized for pre-training. In the preprocessing phase, 244,527 slices from these scans were saved as PNG files and intensity-normalized based on the dataset's mean and standard deviation.

### Downstream Dataset

Three datasets **COVID-19**, **OrgMNIST** and **Brain** are selected to perform downstream tasks to evaluate the effectiveness of the pre-training phase.

## Pretrained Weights

| Method | Pretrain Epochs | website | password |
|-------|:-------:|:-------:|:-------:|
| MAE ViT-S/16 | 300 | https://pan.baidu.com/s/1wE5Ia9L0pOug9ZES7_qM2Q | gmec |
| MAE ViT-B/16 | 300 | https://pan.baidu.com/s/1tkVaVZAGt2Cymus_Qzvu5Q | js8p |
| MAE ViT-L/16 | 300 | https://pan.baidu.com/s/1Gj8wDvwdp2rk3ibz_7XcQA | lojj |
| MAE ViT-H/16 | 300 |  |  |

| Method | Pretrain Epochs | website | password |
|-------|:-------:|:-------:|:-------:|
| SparK ResNet-50 | 300 |  |  |
| SparK ResNet-101 | 300 |  |  |
| SparK ConvNeXt-S | 300 |  |  |
| SparK ConvNeXt-B | 300 |  |  |

| Method | Pretrain Epochs | website | password |
|-------|:-------:|:-------:|:-------:|
| HPM ViT-S/16 | 300 |  |  |
| HPM ViT-B/16 | 300 |  |  |
| HPM ViT-L/16 | 300 |  |  |


## Contact

- 作者：[你的名字]
- 邮箱：[你的邮箱]
- 网站：[你的网站]
