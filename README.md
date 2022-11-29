# Informal settlements detection

## Description

Nowadays a considerable portion of the population lives in informal settlements. These large housing agglomerations are in an irregular land tenure situation and lack regular access to one or more basic housing services (drinking water, electricity, and sewage/septic tank).


The goal of this study is the informal settlement detection using satellite imagery and another kind of information, for subsequent public policy decision-making.

## Requirements 

The tools **GDAL** y [Orfeo Toolbox](https://www.orfeo-toolbox.org/) are used in the first stage, the pre-processing of the data. In the following stages, our packages [satproc](https://github.com/dymaxionlabs/satproc) and [unetseg](https://github.com/dymaxionlabs/satproc) are used for dataset generation and for training and prediction process.

## Notebooks

This repository has a Jupyter Notebooks set, which describes the necessary steps:

1. [Training](notebooks/1_Entrenamiento.ipynb): Satellite imagery and ground truth are processed to generate the training dataset. Then, the model is trained and evaluated.
2. [Prediction](notebooks/2_Prediccion.ipynb): Prediction over the area of interest and prediction results processing.

## :handshake: Contributions

Bugs reports y *pull requests* could be done in the [issues page](https://github.com/dymaxionlabs/adefinir) of this repository. 

## :page_facing_up: License

The code is licensed under Apache 2.0. Refer to [LICENSE.txt](LICENSE.txt).
