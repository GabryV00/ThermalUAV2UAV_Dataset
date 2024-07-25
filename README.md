# ThermalUAV2UAV dataset
This repository contains a dataset of thermal images representing UAVs.

There are four types of quadcopters and two types of hexacopters in the dataset. All images were acquired by a DJI Zenmuse XTS, mounted on board a DJI Matrice 210 RTK drone.

The dataset is already supplied divided into train sets, validation sets and test sets. All three folders contain an image folder and a label folder, in YOLO format.

## Experiments 

In addition, there is the notebook containing the experiments conducted on the dataset, using various models and versions of You Only Look Once (YOLO).

## Converting labels

The dataset is provided with label in YOLO format. If you want to convert the labels in COCO format I suggest to use this [YOLO-2-COCO Converter](https://github.com/Taeyoung96/Yolo-to-COCO-format-converter)

## Article

This dataset was born from the study conducted in the following paper:

G.L. Foresti, I. Scagnetto, D. Tavari, G. Voltan, "Thermal UAV2UAV Dataset for Training a Counter UAV system: a Strategic Challenge in Civil and Military Domain", in Strategic Leadership Journal, July 2024.

Please, cite this, if you want to use this dataset in others publications. 

The paper is available at the following link: [Read The Article](https://www.casd.it/pluginfile.php/41518/mod_page/content/17/SLJ_Vol_2_2024_ott.pdf)


