

![logo](media/AiTALS_EOBench.png)

# AiTLAS: Benchmark Arena

*AiTLAS: Benchmark Arena* is an open-source benchmark framework for evaluating state-of-the-art deep learning approaches on Earth Observation (EO) image classification tasks. To this end, we present extensive comparative analyses of more than 400 models that stem from nine different state-of-the-art architectures, comparing them on a variety of multi-class and multi-label classification tasks from 22 datasets with different sizes and properties. We benchmark models trained from scratch as well as in the context of transfer learning, leveraging pre-trained model variants, as it is typically performed in practice. All of the presented approaches are general and readily extendable to many other remote-sensing image classification tasks, not included in this study. To ensure reproducibility as well as to facilitate better usability and further developments, here we provide **all experimental details** including the trained models, model configuration and other dataset details used for for this study.

*AiTLAS: Benchmark Arena* is part of the [**AiTLAS**](https://github.com/biasvariancelabs/aitlas) ecosystem, an open-source library for exploratory and predictive analysis of satellite imaginary pertaining to different remote-sensing tasks. 



# Citation
For attribution in academic contexts, please cite this **[work]()** as
```
@article{aitlas_arena2022,
      title={{Current Trends in Deep Learning for Earth Observation:An Open-source Benchmark Arena for Image Classification}}, 
      author={Ivica Dimitrovski and Ivan Kitanovski and Dragi Kocev and Nikola Simidjievski},
      year={2022},
      journal={arXiv preprint arXiv:},
}
```


# Datasets
### Multi-class datasets
|Dataset| Data source | Data Splits |||
|---|---|---|---|---|
|EuroSAT | [github](https://github.com/phelber/EuroSAT) | <a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/eurosat_train.csv">train</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/eurosat_val.csv">validation</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/eurosat_test.csv">test</a>|
|UC Merced| [url](http://weegee.vision.ucmerced.edu/datasets/landuse.html) |<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/ucmerced_train.csv">train</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/ucmerced_val.csv">validation</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/ucmerced_test.csv">test</a>|
|RSSCN7| [figshare](https://figshare.com/articles/dataset/RSSCN7_Image_dataset/7006946) |<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/rsscn7_train.csv">train</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/rsscn7_val.csv">validation</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/rsscn7_test.csv">test</a>|
|WHU-RS19| [zip](http://captain.whu.edu.cn/datasets/WHU-RS19.zip) |<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/whurs19_train.csv">train</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/whurs19_val.csv">validation</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/whurs19_test.csv">test</a>|
|AID| [baidu](https://pan.baidu.com/s/1mifOBv6#list/path=%2F) |<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/aid_train.csv">train</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/aid_val.csv">validation</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/aid_test.csv">test</a>|
|SIRI-WHU| [figshare](https://figshare.com/articles/dataset/SIRI_WHU_Dataset/8796980) |<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/siriwhu_train.csv">train</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/siriwhu_val.csv">validation</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/siriwhu_test.csv">test</a>|
|RSI-CB256| [one drive](https://onedrive.live.com/?cid=010149152ff2b56d&id=10149152FF2B56D%21105&authkey=!ADyXDc-zA56zPv4) |<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/rsicb256_train.csv">train</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/rsicb256_val.csv">validation</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/rsicb256_test.csv">test</a>|
|RESISC45| [one drive](https://onedrive.live.com/?authkey=%21AHHNaHIlzp%5FIXjs&cid=5C5E061130630A68&id=5C5E061130630A68%21107&parId=5C5E061130630A68%21112&action=locate) |<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/resisc45_train.csv">train</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/resisc45_val.csv">validation</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/resisc45_test.csv">test</a>|
|PatternNet| [gdrive](https://drive.google.com/file/d/127lxXYqzO6Bd0yZhvEbgIfz95HaEnr9K/view) |<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/patternnet_train.csv">train</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/patternnet_val.csv">validation</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/patternnet_test.csv">test</a>|
|CLRS| [baidu](https://pan.baidu.com/share/init?surl=Xnw9k20Df_ICmkXdvasVqg) |<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/clrs_train.csv">train</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/clrs_val.csv">validation</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/clrs_test.csv">test</a>|
|RSD46-WHU| [baidu](https://pan.baidu.com/s/1mMDKUu02V0s8rXstewv26A) |<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/rsd46whu_train.csv">train</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/rsd46whu_val.csv">validation</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/rsd46whu_test.csv">test</a>|
|SAT6| [gdrive](https://drive.google.com/uc?id=0B0Fef71_vt3PUkZ4YVZ5WWNvZWs&export=download) |<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/sat6_train.csv">train</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/sat6_val.csv">validation</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/sat6_test.csv">test</a>|
|Optimal31| [gdrive](https://drive.google.com/file/d/1Fk9a0DW8UyyQsR8dP2Qdakmr69NVBhq9/view) |<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/optimal31_train.csv">train</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/optimal31_val.csv">validation</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/optimal31_test.csv">test</a>|
|Brazilian Coffee Scenes| [zip](http://www.patreo.dcc.ufmg.br/wp-content/uploads/2017/11/brazilian_coffee_dataset.zip) |<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/bcs_train.csv">train</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/bcs_val.csv">validation</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/bcs_test.csv">test</a>|
|So2Sat| [url](http://doi.org/10.14459/2018MP1454690) |<a href="https://dataserv.ub.tum.de/s/m1483140/download?path=%2F&files=training.h5">train</a>|<a href="https://dataserv.ub.tum.de/s/m1483140/download?path=%2F&files=validation.h5">validation</a>|<a href="https://dataserv.ub.tum.de/s/m1483140/download?path=%2F&files=testing.h5">test</a>|

###  Multi-label datasets

|Dataset| Data source | Data Splits |||
|---|---|---|---|---|
|UC Merced (mlc)|[gdrive](https://drive.google.com/file/d/1DtKiauowCB0ykjFe8v0OVvT76rEfOk0v/view)|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/ucmercedmultilabel_train.csv">train</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/ucmercedmultilabel_val.csv">validation</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/ucmercedmultilabel_test.csv">test</a>|
|AID (mlc)|[github](https://github.com/Hua-YS/AID-Multilabel-Dataset)|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/aidmultilabel_train.csv">train</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/aidmultilabel_val.csv">validation</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/aidmultilabel_test.csv">test</a>|
|DFC15|[gdrive](https://drive.google.com/drive/folders/1TKGS6TIRxQ6a7gdaj0cHs-mRCtv_J1HA)|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/dfc15_train.csv">train</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/dfc15_val.csv">validation</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/dfc15_test.csv">test</a>|
|Planet UAS|[kaggle](https://www.kaggle.com/c/planet-understanding-the-amazon-from-space/overview)|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/planetuas_train.csv">train</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/planetuas_val.csv">validation</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/planetuas_test.csv">test</a>|
|MLRSNet|[mendeley](https://data.mendeley.com/datasets/7j9bv9vwsx/2)|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/mlrsnet_train.csv">train</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/mlrsnet_val.csv">validation</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/mlrsnet_test.csv">test</a>|
|BigEarthNet 19|[url](http://bigearth.net/)|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/bigearthnet_train.csv">train</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/bigearthnet_val.csv">validation</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/bigearthnet_test.csv">test</a>|
|BigEarthNet 43|[url](http://bigearth.net/)|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/bigearthnet_train.csv">train</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/bigearthnet_val.csv">validation</a>|<a href="https://github.com/biasvariancelabs/LULC/blob/main/splits/bigearthnet_test.csv">test</a>|

# Performance
## Pretrained [ImageNet-1K]

 ### Multi-class datasets

*Top-1 Accuracy (model rank wrt dataset)

| **Dataset\Model** | **AlexNet (8.93)** | **VGG16 (7.67)** | **ResNet50 (4.07)** | **ResNet152 (3.27)** | **DenseNet161 (2.6)** | **EfficientNetB0 (5.13)** | **ConvNeXt (4.8)** | **ViT (2.73)** | **MLP Mixer (4.67)** |
|-------------------|--------------------|------------------|---------------------|----------------------|-----------------------|---------------------------|--------------------|----------------|----------------------|
| **WHU-RS19**      | 93.532 (9)         | 99.005 (5)       | 99.502 (2)          | 98.01 (8)            | 100 (1)               | 99.502 (2)                | 99.005 (5)         | 99.502 (2)     | 98.507 (7)           |
| **Optimal31**     | 80.914 (9)         | 88.71 (8)        | 92.204 (6)          | 92.473 (5)           | 94.355 (2)            | 91.667 (7)                | 93.011 (3)         | 94.624 (1)     | 92.742 (4)           |
| **UC merced**     | 92.143 (9)         | 95.476 (8)       | 98.571 (2)          | 98.81 (1)            | 98.333 (4)            | 98.571 (2)                | 97.857 (7)         | 98.333 (4)     | 98.333 (4)           |
| **SIRI-WHU**      | 92.292 (9)         | 93.958 (8)       | 95 (6)              | 96.25 (1)            | 95.625 (3)            | 95 (6)                    | 96.25 (1)          | 95.625 (3)     | 95.208 (5)           |
| **RSSCN7**        | 91.964 (9)         | 93.929 (8)       | 95 (4)              | 95 (4)               | 94.821 (6)            | 95.536 (2)                | 94.643 (7)         | 95.893 (1)     | 95.179 (3)           |
| **BCS**           | 89.583 (9)         | 90.972 (8)       | 92.014 (4)          | 92.361 (3)           | 92.708 (2)            | 91.319 (7)                | 91.493 (6)         | 92.014 (4)     | 93.056 (1)           |
| **AID**           | 92.9 (9)           | 96.1 (8)         | 96.55 (6)           | 97.2 (3)             | 97.25 (2)             | 96.25 (7)                 | 96.95 (4)          | 97.75 (1)      | 96.7 (5)             |
| **CLRS**          | 84.1 (9)           | 89.9 (8)         | 91.567 (4)          | 91.9 (3)             | 92.2 (2)              | 90.5 (6)                  | 91.1 (5)           | 93.2 (1)       | 90.1 (7)             |
| **RSI-CB256**     | 99.354 (8)         | 99.051 (9)       | 99.677 (5)          | 99.859 (1)           | 99.737 (3)            | 99.717 (4)                | 99.596 (7)         | 99.758 (2)     | 99.657 (6)           |
| **Eurosat**       | 97.574 (9)         | 98.148 (8)       | 98.833 (4)          | 99 (1)               | 98.889 (3)            | 98.907 (2)                | 98.778 (5)         | 98.722 (7)     | 98.741 (6)           |
| **PatternNet**    | 99.161 (9)         | 99.424 (8)       | 99.737 (1)          | 99.49 (7)            | 99.737 (1)            | 99.539 (6)                | 99.671 (4)         | 99.655 (5)     | 99.704 (3)           |
| **RESISC45**      | 90.492 (9)         | 93.905 (8)       | 96.46 (4)           | 96.54 (2)            | 96.508 (3)            | 94.873 (7)                | 96.27 (5)          | 97.079 (1)     | 95.952 (6)           |
| **RSD46-WHU**     | 90.646 (9)         | 92.422 (8)       | 94.158 (4)          | 94.404 (2)           | 94.507 (1)            | 93.387 (7)                | 93.627 (6)         | 94.238 (3)     | 93.673 (5)           |
| **So2Sat**        | 59.203 (9)         | 65.375 (6)       | 61.903 (8)          | 65.169 (7)           | 65.756 (5)            | 65.801 (4)                | 66.169 (3)         | 68.551 (1)     | 67.066 (2)           |
| **SAT6**          | 99.98 (9)          | 99.993 (7)       | 100 (1)             | 100 (1)              | 100 (1)               | 99.988 (8)                | 99.999 (4)         | 99.998 (5)     | 99.995 (6)           |

### Multi-label datasets

*Mean Average Precision mAP (model rank wrt dataset)
| **Dataset\Model**  | **AlexNet (8.86)** | **VGG16 (6.71)** | **ResNet50 (4)** | **ResNet152 (4.29)** | **DenseNet161 (3.86)** | **EfficientNetB0 (5.71)** | **ConvNeXt (3.14)** | **ViT (3.71)** | **MLP Mixer (4.57)** |
|--------------------|--------------------|------------------|------------------|----------------------|------------------------|---------------------------|---------------------|----------------|----------------------|
| **AID (mlc)**            | 75.906 (9)         | 79.893 (7)       | 80.758 (6)       | 80.942 (4)           | 81.708 (2)             | 78.002 (8)                | 82.298 (1)          | 81.539 (3)     | 80.879 (5)           |
| **UC Merced (mlc)**      | 92.638 (9)         | 92.848 (8)       | 95.665 (6)       | 96.01 (5)            | 96.056 (4)             | 95.384 (7)                | 96.431 (2)          | 96.699 (1)     | 96.34 (3)            |
| **DFC15**          | 94.057 (9)         | 96.566 (8)       | 97.662 (3)       | 97.6 (5)             | 97.529 (6)             | 96.787 (7)                | 97.994 (1)          | 97.617 (4)     | 97.941 (2)           |
| **Planet UAS**     | 64.048 (9)         | 65.584 (8)       | 65.528 (4)       | 64.825 (1)           | 66.339 (3)             | 64.157 (6)                | 66.447 (5)          | 66.804 (2)     | 67.33 (7)            |
| **MLRSNet**        | 93.399 (9)         | 94.633 (5)       | 96.272 (6)       | 96.432 (7)           | 96.306 (4)             | 95.391 (8)                | 95.807 (3)          | 96.41 (2)      | 95.049 (1)           |
| **BigEarthNet 43** | 58.554 (9)         | 61.205 (6)       | 66.256 (1)       | 64.066 (5)           | 64.229 (4)             | 64.589 (3)                | 66.166 (2)          | 58.997 (8)     | 59.648 (7)           |
| **BigEarthNet 19** | 77.147 (8)         | 78.418 (5)       | 79.983 (2)       | 79.776 (3)           | 79.686 (4)             | 80.221 (1)                | 77.147 (8)          | 77.31 (6)      | 77.288 (7)           |

# Models

All trained models are available **[here](https://drive.google.com/drive/folders/1lTnPsMyyLv9XoPu3cMmE_h6NPkj_WCH8?usp=sharing)**

## Model list 

<table>
<tr><th> Multi-class classification tasks</th><th> Multi-label classification tasks</th></tr>
<tr><td>




| Dataset        | Model          | from scratch         | pretrained [ImageNet1K] |
|----------------|----------------|----------------------|-------------------------|
| AID            | AlexNet        | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | VGG16          | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet50       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet152      | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | DenseNet161    | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | EfficientNetB0 | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ViT            | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | MLPMixer       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ConvNeXt       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
| BCS            | AlexNet        | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | VGG16          | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet50       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet152      | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | DenseNet161    | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | EfficientNetB0 | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ViT            | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | MLPMixer       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ConvNeXt       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
| CLRS           | AlexNet        | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | VGG16          | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet50       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet152      | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | DenseNet161    | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | EfficientNetB0 | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ViT            | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | MLPMixer       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ConvNeXt       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
| Eurosat        | AlexNet        | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | VGG16          | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet50       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet152      | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | DenseNet161    | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | EfficientNetB0 | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ViT            | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | MLPMixer       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ConvNeXt       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
| Optimal31      | AlexNet        | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | VGG16          | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet50       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet152      | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | DenseNet161    | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | EfficientNetB0 | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ViT            | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | MLPMixer       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ConvNeXt       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
| PatternNet     | AlexNet        | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | VGG16          | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet50       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet152      | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | DenseNet161    | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | EfficientNetB0 | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ViT            | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | MLPMixer       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ConvNeXt       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
| RESISC45       | AlexNet        | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | VGG16          | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet50       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet152      | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | DenseNet161    | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | EfficientNetB0 | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ViT            | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | MLPMixer       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ConvNeXt       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
| RSD46-WHU      | AlexNet        | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | VGG16          | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet50       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet152      | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | DenseNet161    | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | EfficientNetB0 | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ViT            | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | MLPMixer       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ConvNeXt       | :heavy\_check\_mark: | :heavy\_check\_mark:    |



</td><td>

| Dataset        | Model          | from scratch         | pretrained [ImageNet1K] |
|----------------|----------------|----------------------|-------------------------|
| RSI-CB256      | AlexNet        | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | VGG16          | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet50       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet152      | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | DenseNet161    | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | EfficientNetB0 | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ViT            | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | MLPMixer       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ConvNeXt       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
| RSSCN7         | AlexNet        | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | VGG16          | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet50       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet152      | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | DenseNet161    | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | EfficientNetB0 | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ViT            | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | MLPMixer       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ConvNeXt       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
| SAT6           | AlexNet        | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | VGG16          | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet50       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet152      | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | DenseNet161    | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | EfficientNetB0 | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ViT            | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | MLPMixer       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ConvNeXt       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
| SIRI-WHU       | AlexNet        | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | VGG16          | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet50       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet152      | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | DenseNet161    | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | EfficientNetB0 | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ViT            | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | MLPMixer       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ConvNeXt       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
| So2Sat         | AlexNet        | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | VGG16          | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet50       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet152      | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | DenseNet161    | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | EfficientNetB0 | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ViT            | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | MLPMixer       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ConvNeXt       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
| UCMerced       | AlexNet        | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | VGG16          | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet50       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet152      | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | DenseNet161    | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | EfficientNetB0 | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ViT            | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | MLPMixer       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ConvNeXt       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
| WHU-RS19       | AlexNet        | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | VGG16          | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet50       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet152      | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | DenseNet161    | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | EfficientNetB0 | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ViT            | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | MLPMixer       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ConvNeXt       | :heavy\_check\_mark: | :heavy\_check\_mark:    |


</td></tr> </table>



### Multi-label classification tasks

| Dataset        | Model          | from scratch         | pretrained [ImageNet1K] |
|----------------|----------------|----------------------|-------------------------|
| AID (mlc)      | AlexNet        | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | VGG16          | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet50       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet152      | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | DenseNet161    | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | EfficientNetB0 | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ViT            | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | MLPMixer       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ConvNeXt       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
| BigEarthNet19  | AlexNet        | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | VGG16          | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet50       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet152      | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | DenseNet161    | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | EfficientNetB0 | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ViT            | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | MLPMixer       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ConvNeXt       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
| BigEarthNet43  | AlexNet        | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | VGG16          | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet50       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet152      | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | DenseNet161    | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | EfficientNetB0 | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ViT            | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | MLPMixer       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ConvNeXt       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
| DFC15          | AlexNet        | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | VGG16          | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet50       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet152      | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | DenseNet161    | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | EfficientNetB0 | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ViT            | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | MLPMixer       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ConvNeXt       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
| MLRSNet        | AlexNet        | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | VGG16          | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet50       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet152      | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | DenseNet161    | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | EfficientNetB0 | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ViT            | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | MLPMixer       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ConvNeXt       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
| PlanetUAS      | AlexNet        | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | VGG16          | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet50       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet152      | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | DenseNet161    | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | EfficientNetB0 | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ViT            | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | MLPMixer       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ConvNeXt       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
| UCMerced (mlc) | AlexNet        | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | VGG16          | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet50       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ResNet152      | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | DenseNet161    | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | EfficientNetB0 | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ViT            | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | MLPMixer       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
|                | ConvNeXt       | :heavy\_check\_mark: | :heavy\_check\_mark:    |
