# OptoSwim
Code collection for [**OptoSwim**], which stands for All-optical interrogation of brain-wide activity in freely swimming larval zebrafish. (https://www.biorxiv.org/content/10.1101/2023.05.24.542114v1).

### Introduction

The code collection here, together with hardware design described in the [paper](https://www.biorxiv.org/content/10.1101/2023.05.24.542114v1), allow us to complete volumetric imaging of brain-wide calcium activity and targeted optogenetic stimulation of specific brain regions in freely swimming larval zebrafish. The three different submodules contain a stable tracking algorithm for zebrafish based on U-Net image processing, a calcium signal extraction and calibration pipeline based on two-color fluorescence imaging, and a real time optogenetic manipulation algorithm based on fast image reconstruction and registration, respectively. 

![fig8](https://github.com/Wenlab/All-optical-interrogation-of-freely-swimming-larval-zebrafish/assets/15085006/83268790-357e-4ea7-a29a-a87ae1a961ff)


You can find how to use the code in the README of each submodule.

*__The submodule doesn't update automatically. So you may use the following links to access the latest repositories of the whole project.__*

[Larval-zebrafish-tracking](https://github.com/Wenlab/Larval-zebrafish-tracking/tree/master)

[Dual-Color-Image-Processing](https://github.com/Wenlab/Dual-Color-Image-Processing)

[Online-Zebrafish-Optogenetic-System](https://github.com/Wenlab/Online-Zebrafish-Optogenetic-System/tree/main)

