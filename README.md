# vision_transformer_cam
use vit to generate class activate map
## 2023年3月17日20:16:09 
使用pascal voc2012数据集训练\
训练时生成cam图
## 2023年3月18日15:29:05
利用cam图生成pseudo seg result
## 2023年3月18日19:59:43
train and validate 完成，其中validate时计算mAP\
修改train.py为train_and_validate.py


## acknowledgments
Rewrite the code using the following repository\
https://github.com/WZMIAOMIAO/deep-learning-for-image-processing/tree/master/pytorch_classification/vision_transformer