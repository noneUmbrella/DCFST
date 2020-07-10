# DCFST
Learning Feature Embeddings for Discriminant Model based Tracking

Accepted by ECCV2018.

DCFST is a simple yet effective tracker. This project provides the training and test codes of DCFST. It can produce the accuracy of DCFST on six popular tracking benchmarks, OTB2015, NfS, TrackingNet, GOT10k, VOT2018, and VOT2019. (I will gradually add parts of the code as soon as I have free time to deal with this project.)

Specifically, DCFST with resnet-18, i.e. DCFST-18, obtains the AUC score of 0.709 on OTB2015, 0.634 on NFS, 0.610 on GOT10k, 0.739 on TrackingNet, 0.416 on VOT2018, and 0.361 on VOT2019, DCFST with resnet-50, i.e. DCFST-50, obtains the AUC score of 0.641 on NFS, 0.638 on GOT10k, 0.752 on TrackingNet, 0.452 on VOT2018. Under the following hardwares, DCFST-18 and DCFST-50 run around 35FPS and 25FPS, respectively.

Thanks for the handsome work, ATOM, by Martin Danelljan. This project is highly based on pytracking (https://github.com/visionml/pytracking). Particularly, it is based on the early version (pytorch 0.4.1) of pytracking (https://github.com/visionml/pytracking/tree/pytorch041). Therefore, if there are any missing documents and operation descriptions due to my carelessness, please refer to the corresponding section in pytracking.

Requirements:
Intel(R) Xeon(R) CPU E5-2630 v4 @ 2.20GHz CPU
TITAN X(Pascal) or TITAN 1080Ti GPU
8.0 CUDA
numpy  1.16.2
numpy-base  1.16.2
python  3.7.3
torchvision  0.2.1
pytorch  0.4.1
Pillow 5.4.1
pandas 1.0.3

*** NOTE *** We try our best to let everyone enjoy the above accuracy of DCFST accurately. The ATOM in pytracking is stochastic. In order to eliminate the randomness as much as possible, we make a small change to ATOM. For users, please ensure the versions of softwares and environments you used are the same as above. BTW, there may be more version requirements, those are all we can think of so far.

Project in process ...
