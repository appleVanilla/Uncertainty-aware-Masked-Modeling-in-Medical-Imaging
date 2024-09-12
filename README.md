# Uncertainty-aware Masked Modeling in Medical Imaging

The detailed code will be released soon. :construction:.

## Data Preparation

### Pretraining Dataset

The publicly accessible **LIDC-IDRI** dataset, comprising lung CT scans of 1,010 patients in DICOM format, was utilized for pre-training. In the preprocessing phase, 244,527 slices from these scans were saved as PNG files and intensity-normalized based on the dataset's mean and standard deviation.

Download the LIDC-IDRI Dataset from here: https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=1966254

### Downstream Dataset

Two datasets **COVID-19** and **OrgMNIST** are selected to perform downstream tasks to evaluate the effectiveness of the pre-training phase.
We tested our pre-training on two CT classification tasks:

- **COVID-19**: Covid classification on lung CT scans (From Grand Challenge https://covid-ct.grand-challenge.org/ or https://doi.org/10.48550/arXiv.2003.13865)
- **OrgMNIST**: Multi-class classification of 11 body organs on patches cropped around organs from abdominal CT scans (From MedMNIST Challenges https://medmnist.com/ or https://doi.org/10.1038/s41597-022-01721-8)

## Pretrained Weights

| Method | Pretrain Epochs | website | password |
|-------|:-------:|:-------:|:-------:|
| MAE ViT-S/16 | 300 | https://pan.baidu.com/s/1wE5Ia9L0pOug9ZES7_qM2Q | gmec |
| MAE ViT-B/16 | 300 | https://pan.baidu.com/s/1tkVaVZAGt2Cymus_Qzvu5Q | js8p |
| MAE ViT-L/16 | 300 | https://pan.baidu.com/s/1Gj8wDvwdp2rk3ibz_7XcQA | lojj |
| MAE ViT-H/16 | 300 | https://pan.baidu.com/s/1yb5T78kYl4BNPu026J09sg | v6lo |

| Method | Pretrain Epochs | website | password |
|-------|:-------:|:-------:|:-------:|
| SparK ResNet-50 | 300 | https://pan.baidu.com/s/1Qk03S1ECwN5pVE8iBFrUJQ | idag |
| SparK ConvNeXt-S | 300 | https://pan.baidu.com/s/1AkUriGNpd704KuPYMpMYlA | c3sc |

| Method | Pretrain Epochs | website | password |
|-------|:-------:|:-------:|:-------:|
| HPM ViT-S/16 | 300 | https://pan.baidu.com/s/1ThlXk64sTVUDlkC7iTk_Tw | 0vt1 |
| HPM ViT-B/16 | 300 | https://pan.baidu.com/s/1jdak7-xGVu6sPEQ2NOpvQw | gh3k |

