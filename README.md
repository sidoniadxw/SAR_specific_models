# SAR_specific_models

This project provides some SAR specific models which have a strong ability to extract spatial features of single-polarization Synthetic Aperture Radar images.

A novel deep learning framework Deep SAR-Net has been also proposed for SLC SAR images, together with trained models.

## reference
[1] Imbalanced Large-Scale Complex Land Cover Classification of High-Resolution SAR Images with Deep Transfer Learning, submitted to IEEE GRSL (undergoing review)

[2] What, Where and How to Transfer in SAR Target Recognition Based on Deep CNNs, submitted to IEEE TGRS (undergoing review)
preprint version https://arxiv.org/abs/1906.01379

[3] Deep SAR-Net: Learning Objects from Signals, submitted to ISPRS Journal of Photogrammetry and Remote Sensing (undergoing review)

## Environment
pytorch 0.4.0
python 3.6

## SAR specific model zoo
./models/resnet18_I_nwpu_cate45_tsx_level1_cate7_col36_imb_ce+topk+.pth
  
  see ref[1]

./models/resnet18_tsx_mstar_epoch7.pth
  
  see ref[1] achieving an overall accuracy of 99.46% on MSTAR 10-class target recognition task

./models/alexnet_tsx.pth

  see ref[2]

./models/alexnet_tsx_mstar_iter1920.pth
  
  see ref[2] achieving an overall accuracy of 99.34% on MSTAR 10-class target recognition task
  
./models/slc_joint_deeper_3_F.pth
  
  see ref[3] training with 90% data
