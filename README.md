# YOLOv7 for Oriented Object Detection

<a href="https://colab.research.google.com/drive/1NyV38OCD1T7fUE3E5TB_du-bqG1WSGY9?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>

<div align="center">
    <a href="./">
        <img src="./figure/map_airport.png" width="79%"/>
    </a>
</div>

<div align="center">
    <a href="./">
        <img src="./figure/train_batch0.jpg" width="79%"/>
    </a>
</div>

<div align="center">
    <a href="./">
        <img src="./figure/confusion_matrix.png" width="79%"/>
    </a>
</div>

<div align="center">
    <a href="./">
        <img src="./figure/results.png" width="79%"/>
    </a>
</div>

Implementation of [YOLOv7](https://arxiv.org/abs/2207.02696), [Circular Smooth Label](https://arxiv.org/abs/2003.05597v2) and [YOLOv5-OBB](https://github.com/hukaixuan19970627/yolov5_obb) as part of the final graduation project at [Federal University of Santa Maria, Brazil](https://www.ufsm.br/) 

## Performance 

The results on DOTA_subsize1024_gap200_rate1.0 test-dev set are shown in the table below.

 |Model<br><sup>(download link) |Size<br><sup>(pixels) | TTA<br><sup>(multi-scale/<br>rotate testing) | OBB mAP<sup>test<br><sup>0.5<br>DOTAv1.5 | Speed<br><sup>T4 b8<br>(ms) |params<br><sup>(M) |FLOPs<br><sup>@1024 (B) 
 | ----                                                                                                                                                           | ---  | ---   | ---   | --- | --- | ---
 |yolov7 [[google](https://drive.google.com/file/d/10zxuTON_1XxZ3SKzjZaWPdwrV0SF26ed/view?usp=sharing)]  |1024  | ×     |**77.9**      |**37.6**      |**37.5**   |**106.5**

## Installation

Please refer to [install.md](./docs/install.md) for installation and dataset preparation.

## Getting Started 

This repo is based on [YOLOv7](https://arxiv.org/abs/2207.02696). Please refer to [getStarted.md](./docs/getStarted.md) for the basic usage.

## Re-parameterization

See [reparameterization.ipynb](tools/reparameterization.ipynb)

## Acknowledgements

<details><summary> <b>Expand</b> </summary>

* [YOLOv5](https://github.com/ultralytics/yolov5)
* [YOLOv7](https://arxiv.org/abs/2207.02696)
* [Circular Smooth Label](https://arxiv.org/abs/2003.05597v2)
* [YOLOv5-OBB](https://github.com/hukaixuan19970627/yolov5_obb)
* [CAPTAIN-WHU/DOTA_devkit](https://github.com/CAPTAIN-WHU/DOTA_devkit)

</details>
