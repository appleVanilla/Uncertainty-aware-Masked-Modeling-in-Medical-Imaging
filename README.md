# Mask-awared-Hard-Patches-Mining-in-Mask-Image-Modeling

The project is still under construction :construction:.

## Data Preparation

### Pretraining Dataset

The publicly accessible **LIDC-IDRI** dataset, comprising lung CT scans of 1,010 patients in DICOM format, was utilized for pre-training. In the preprocessing phase, 244,527 slices from these scans were saved as PNG files and intensity-normalized based on the dataset's mean and standard deviation.

Download the LIDC-IDRI Dataset from here: https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=1966254

### Downstream Dataset

Three datasets **COVID-19**, **OrgMNIST** and **Brain** are selected to perform downstream tasks to evaluate the effectiveness of the pre-training phase.
We tested our pre-training on three CT classification tasks:

- **COVID-19**: Covid classification on lung CT scans (From Grand Challenge https://covid-ct.grand-challenge.org/ or https://doi.org/10.48550/arXiv.2003.13865)
- **OrgMNIST**: Multi-class classification of 11 body organs on patches cropped around organs from abdominal CT scans (From MedMNIST Challenges https://medmnist.com/ or https://doi.org/10.1038/s41597-022-01721-8)
- **Brain**: Brain hemorrhage classification on brain CT scans on an internal dataset of the Ulm Univerity Medical Center

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

