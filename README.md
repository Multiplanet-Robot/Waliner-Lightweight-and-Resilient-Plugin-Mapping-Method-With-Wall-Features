# Waliner: Lightweight and Resilient Plugin Mapping Method With Wall Features for Visually Challenging Indoor Environments

# Organizations and participants
 ![](https://www.lge.co.kr/lgekor/asset/company/images/about/ci_img03.jpg)
 <p align="center">
 <img src="https://github.com/user-attachments/assets/1b1c1e71-c8ec-4f00-a9ed-2debe772af98" width="600" height="300"/>
</p>

* DongKi Noh, Advanced Robotics Lab. LG Electronics Inc. (E-mail: dongki.noh@lge.com, dongki.noh@kaist.ac.kr)
* Byunguk Lee, the School of Electronic Engineering at KIT (Kumoh National Institute of Technology) (E-mail: qud159@kumoh.ac.kr)
* Hanngyoo Kim, the School of Electronic Engineering at KIT (Kumoh National Institute of Technology) (E-mail: rlarb100@kumoh.ac.kr)
* SeungHwan Lee, the School of Electronic Engineering at KIT (Kumoh National Institute of Technology) (E-mail: leesh@kumoh.ac.kr)
* Jeongsik Choi, Advanced Robotics Lab. LG Electronics Inc. (E-mail: jeongs.choi@lge.com)
* Seungmin Baek, Advanced Robotics Lab. LG Electronics Inc. (E-mail: seungmin2.baek@lge.com)

# Framework
## Overall SLAM pipeline with the proposed method, Waliner: 

The colored box represents our proposed method, which aims to refine the initial pose using the Manhattan frame (MF) generated from lines extracted from walls using a deep learning-based method and a neural processing unit (NPU). 
Additionally, we leverage VINS and RTAB-MAP for the initial pose estimation at the $k$-th step and 3D mapping, respectively. The refined pose enhances the accuracy of the SLAM process, particularly in environments with challenging visual features.
<p align="center">
<img src=https://github.com/user-attachments/assets/6e9b728a-74b8-4b5f-93a5-0dcfe425759f width="900" height="600">
</p>

# Demo
## Performance comparison on ``Extended scenario \#2'' dataset (ours)
<p align="center">
<img src=https://github.com/user-attachments/assets/aa3015aa-ad64-4cd1-925f-e233dd7d8d57 width="900" height="600">
</p>

<p align="center">
<img src=https://github.com/user-attachments/assets/083e8266-530a-4f34-823f-304c86d2d4d9  width="900" height="600">
</p>

## Performance comparison on ``Scenario I and II'' dataset (ours)
<p align="center">
<img src=https://github.com/user-attachments/assets/f5d0849b-ff5b-49e4-825a-9dcb6183045b width="900" height="900">
</p>

## Performance comparison on ``Extended scenario #1, #2, and #4'' dataset (ours)
<p align="center">
<img src=https://github.com/user-attachments/assets/814071dd-697a-4753-aba1-024cc247b2c7 width="900" height="600">
</p>

# Environments
## Lighting conditions
<p align="center">
<img src=https://github.com/user-attachments/assets/465e7a3d-ac28-4a3b-858f-b3231d0037b1 width="900" height="600">
</p>

## Moving objects (humans)
<p align="center">
<img src=https://github.com/user-attachments/assets/64a62690-3a39-4afa-809e-fd35c4163a11 width="900" height="600">
</p>

# Quantitative results
The proposed algorithm was evaluated on a public dataset (OpenLoris [28]) as well as our dataset.
<p align="center">
<img src=https://github.com/user-attachments/assets/729c70d0-2e84-4027-b625-194c4fdda9cf width="900" height="200">
</p>

[28] Q. She, F. Feng, X. Hao, Q. Yang, C. Lan, V. Lomonaco, X. Shi, Z. Wang, Y. Guo, Y. Zhang, F. Qiao, and R. H. M. Chan, “OpenLORISObject:
A robotic vision dataset and benchmark for lifelong deep learning,” in Proc. IEEE Int. Conf. Robot. Autom. (ICRA), 2020, pp.4767–4773.
