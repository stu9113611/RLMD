# Road Line and Marking Dataset

![image](https://github.com/stu9113611/RLMD/blob/main/teaser.png)

This repository contains dataset download link and supporting code for our paper [RLMD: A Dataset for Road Marking Segmentation](https://ieeexplore.ieee.org/document/10226935).

## Table of Contents
1. [Introduction](#introduction)
1. [Download](#download)
1. [Evaluation](#evaluation)
1. [Citation](#citation)

## Introduction

RLMD is a road line and marking semantic segmentation dataset containing 2138 driving scene images and annotations. The annotations is manually annotated with 25 categories and saved in polygon mask format. Information about the categories is shown bellow, or you can download the [csv](https://github.com/stu9113611/RLMD/blob/main/classes.csv).

|id |name                |abbr|r  |g  |b  |
|---|--------------------|----|---|---|---|
|0  |background          |BG  |0  |0  |0  |
|1  |box junction        |BJ  |255|242|0  |
|2  |crosswalk           |CW  |34 |117|76 |
|3  |stop line           |SL  |61 |72 |204|
|4  |solid single white  |SSW |237|28 |36 |
|5  |solid single yellow |SSY |163|73 |164|
|6  |solid single red    |SSR |185|122|87 |
|7  |solid double white  |SDW |136|0  |21 |
|8  |solid double yellow |SDY |112|146|190|
|9  |dashed single white |DSW |181|230|29 |
|10 |dashed single yellow|DSY |153|217|234|
|11 |left arrow          |LA  |158|159|76 |
|12 |straight arrow      |SA  |121|138|134|
|13 |right arrow         |RA  |41 |64 |96 |
|14 |left straight arrow |LSA |7  |102|146|
|15 |right straight arrow|RSA |247|153|255|
|16 |channelizing line   |CL  |255|204|153|
|17 |motor prohibited    |MP  |155|255|153|
|18 |slow                |SLOW|255|153|173|
|19 |motor priority lane |MPL |230|224|147|
|20 |motor waiting zone  |MWZ |35 |27 |87 |
|21 |left turn box       |LTB |193|158|155|
|22 |motor icon          |MI  |109|29 |78 |
|23 |bike icon           |BI  |3  |164|204|
|24 |parking lot         |PL  |175|157|185|

To be continued...


## Download

Please download the dataset from [here](https://drive.google.com/drive/folders/18-Lnz2MaPQWSOJ8aK1ikkwXLLdjImYOA?usp=sharing).

The original images & annotations are in 4K resolution, and will be uploaded soon...

## Evaluation

To be continued...


## Citation

If you use our dataset in your work, please cite the following paper.
```
@inproceedings{
    hsiao2023rlmd,
    title={RLMD: A Dataset for Road Marking Segmentation},
    author={Hsiao, Heng-Chih and Cai, Yi-Chang and Lin, Huei-Yung and Chiu, Wei-Chen and Chan, Chiao-Tung},
    booktitle={2023 International Conference on Consumer Electronics-Taiwan (ICCE-Taiwan)},
    pages={427--428},
    year={2023},
    organization={IEEE}
}
```
