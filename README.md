

![logo](media/AiTALS_EOBench.png)

# AiTLAS: Benchmark Arena

We present **AiTLAS: Benchmark Arena** -- an open-source benchmark suite for evaluating state-of-the-art deep learning approaches for image classification in Earth Observation (EO). To this end, we present a comprehensive comparative analysis of more than 500 models derived from ten different state-of-the-art architectures and compare them to a variety of multi-class and multi-label classification tasks from 22 datasets with different sizes and properties. In addition to models trained entirely on these datasets, we benchmark models trained in the context of transfer learning, leveraging pre-trained model variants, as it is typically performed in practice. All presented approaches are general and can be easily extended to many other remote sensing image classification tasks not considered in this study. To ensure reproducibility and facilitate better usability and further developments, *all of the experimental resources* including the trained models, model configurations and processing details of the datasets (with their corresponding splits used for training and evaluating the models) are available on this repository. 

For further details, please refer to our paper *[Current Trends in Deep Learning for Earth Observation: An Open-source Benchmark Arena for Image Classification](https://www.sciencedirect.com/science/article/pii/S0924271623000205)*, ISPRS Journal of Photogrammetry and Remote Sensing, Vol.197, pp 18-35

*AiTLAS: Benchmark Arena* is part of the [**AiTLAS**](https://github.com/biasvariancelabs/aitlas) ecosystem, an open-source library for exploratory and predictive analysis of satellite imaginary pertaining to different remote-sensing tasks. 



# Citation
For attribution in academic contexts, please cite this **[work](https://www.sciencedirect.com/science/article/pii/S0924271623000205)** as
```
@article{aitlas_arena2022,
      title={{Current Trends in Deep Learning for Earth Observation:An Open-source Benchmark Arena for Image Classification}}, 
      author={Ivica Dimitrovski and Ivan Kitanovski and Dragi Kocev and Nikola Simidjievski},
      journal = {ISPRS Journal of Photogrammetry and Remote Sensing},
      volume = {197},
      pages = {18-35},
      year = {2023},
      issn = {0924-2716},
}

```


# Datasets

You can obtain each dataset (with the respective splits) on the links below. If you use these datasets please cite the original authors accordingly. The references are provided in Tables 1 and 2 in our **[paper](https://www.sciencedirect.com/science/article/pii/S0924271623000205)**. You can find more details about each dataset in the supplementary material of the paper as well as on our [AiTLAS Semantic Data Catalog](http://eodata.bvlabs.ai/).

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

*Top-1 Accuracy

| **Dataset\Model**| **AlexNet** | **VGG16** | **ResNet50**    | **ResNet152**   | **DenseNet161** | **EfficientNetB0** | **ViT**         | **MLPMixer** | **ConvNeXt**   | **SwinT**       |
|----------------------------------|-------------|-----------|-----------------|-----------------|-----------------|--------------------|-----------------|--------------|----------------|-----------------|
| WHU-RS19                         | 93.532      | 99.005    | 99.502          | 98.01           | **100**    | 99.502             | 99.502          | 98.507       | 99.005         | 99.502          |
| Optimal31                        | 80.914      | 88.71     | 92.204          | 92.473          | 94.355          | 91.667             | **94.624** | 92.742       | 93.011         | 92.473          |
| UC Merced                        | 92.143      | 95.476    | 98.571          | **98.810** | 98.333          | 98.571             | 98.333          | 98.333       | 97.857         | 98.571          |
| SIRI-WHU                         | 92.292      | 93.958    | 95              | **96.25**  | 95.625          | 95                 | 95.625          | 95.208       | **96.25** | 95.625          |
| RSSCN7                           | 91.964      | 93.929    | 95              | 95              | 94.821          | 95.536             | **95.893** | 95.179       | 94.643         | 95.179          |
| BCS                              | 89.583      | 90.972    | 92.014          | 92.361          | 92.708          | 91.319             | 92.014          | 93.056       | 91.493         | **93.403** |
| AID                              | 92.9        | 96.1      | 96.55           | 97.2            | 97.25           | 96.25              | **97.750** | 96.7         | 96.95          | 97.4            |
| CLRS                             | 84.1        | 89.9      | 91.567          | 91.9            | 92.2            | 90.5               | **93.200** | 90.1         | 91.1           | 92.533          |
| RSI-CB256                        | 99.354      | 99.051    | 99.677          | **99.859** | 99.737          | 99.717             | 99.758          | 99.657       | 99.596         | 99.677          |
| Eurosat                          | 97.574      | 98.148    | 98.833          | **99**     | 98.889          | 98.907             | 98.722          | 98.741       | 98.778         | 98.944          |
| PatternNet                       | 99.161      | 99.424    | **99.737** | 99.49           | **99.737** | 99.539             | 99.655          | 99.704       | 99.671         | 99.688          |
| RESISC45                         | 90.492      | 93.905    | 96.46           | 96.54           | 96.508          | 94.873             | **97.079** | 95.952       | 96.27          | 96.587          |
| RSD46-WHU                        | 90.646      | 92.422    | 94.158          | 94.404          | **94.507** | 93.387             | 94.238          | 93.673       | 93.627         | 93.536          |
| So2Sat                           | 59.203      | 65.375    | 61.903          | 65.169          | 65.756          | 65.801             | **68.551** | 67.066       | 66.169         | 65.950          |
| SAT6                             | 99.98       | 99.993    | **100**    | **100**    | **100**    | 99.988             | 99.998          | 99.995       | 99.999         | 99.999          |

### Multi-label datasets

*Mean Average Precision mAP 
| **Dataset\Model** | **AlexNet** | **VGG16** | **ResNet50** | **ResNet152** | **DenseNet161** | **EfficientNetB0** | **ViT** | **MLPMixer** | **ConvNeXt**    | **SwinT**       |
|---------------------------------|-------------|-----------|--------------|---------------|-----------------|--------------------|---------|--------------|-----------------|-----------------|
| AID (mlc)                       | 75.906      | 79.893    | 80.758       | 80.942        | 81.708          | 78.002             | 81.539  | 80.879       | **82.298** | 82.254          |
| UC Merced (mlc)                 | 92.638      | 92.848    | 95.665       | 96.01         | 96.056          | 95.384             | 96.699  | 96.34        | 96.431          | **96.831** |
| DFC15                           | 94.057      | 96.566    | 97.662       | 97.6          | 97.529          | 96.787             | 97.617  | 97.941       | 97.994          | **98.111** |
| Planet UAS                      | 64.048      | 65.584    | 65.528       | 64.825        | 66.339          | 64.157             | 66.804  | 67.330       | 66.447          | **67.837** |
| MLRSNet                         | 93.399      | 94.633    | 96.272       | 96.432        | 96.306          | 95.391             | 96.41   | 95.049       | 95.807          | **96.620** |
| BigEarthNet 19                  | 77.147      | 78.418    | 79.983       | 79.776        | 79.686          | 80.221             | 77.31   | 77.288       | 80.283          | **81.384** |
| BigEarthNet 43                  | 58.554      | 61.205    | 66.256       | 64.066        | 64.229          | 64.589             | 58.997  | 59.648       | 66.166          | **67.733** |
# Models

All trained models are available **[here](https://drive.google.com/drive/folders/1lTnPsMyyLv9XoPu3cMmE_h6NPkj_WCH8?usp=sharing)**.

## Model list 
| Model          | from scratch         | pretrained [ImageNet1K] | config files          | logs                 |
|----------------|----------------------|-------------------------|----------------------|----------------------|
| AlexNet        | :heavy\_check\_mark: | :heavy\_check\_mark:    | :heavy\_check\_mark: | :heavy\_check\_mark: |
| VGG16          | :heavy\_check\_mark: | :heavy\_check\_mark:    | :heavy\_check\_mark: | :heavy\_check\_mark: |
| ResNet50       | :heavy\_check\_mark: | :heavy\_check\_mark:    | :heavy\_check\_mark: | :heavy\_check\_mark: |
| ResNet152      | :heavy\_check\_mark: | :heavy\_check\_mark:    | :heavy\_check\_mark: | :heavy\_check\_mark: |
| DenseNet161    | :heavy\_check\_mark: | :heavy\_check\_mark:    | :heavy\_check\_mark: | :heavy\_check\_mark: |
| EfficientNetB0 | :heavy\_check\_mark: | :heavy\_check\_mark:    | :heavy\_check\_mark: | :heavy\_check\_mark: |
| Vision Transformer | :heavy\_check\_mark: | :heavy\_check\_mark:    | :heavy\_check\_mark: | :heavy\_check\_mark: |
| MLPMixer       | :heavy\_check\_mark: | :heavy\_check\_mark:    | :heavy\_check\_mark: | :heavy\_check\_mark: |
| ConvNeXt       | :heavy\_check\_mark: | :heavy\_check\_mark:    | :heavy\_check\_mark: | :heavy\_check\_mark: |
| Swin Transformer  | :heavy\_check\_mark: | :heavy\_check\_mark:    | :heavy\_check\_mark: | :heavy\_check\_mark: |

