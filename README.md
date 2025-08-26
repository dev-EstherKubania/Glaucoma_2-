# Glaucoma_2-
This is a machine learning model for glaucoma detection using publicly available dataset from kaggle. https://www.kaggle.com/datasets/deathtrooper/multichannel-glaucoma-benchmark-dataset
Using GPU run the code from data download to model training on Colab 
The code is made using resnet50-cnn architecture.
Segmentation.py shows masks on fundus images while glaucoma_prediction.py predicts whether a patient has glaucoma or not based on provided image. 
Expected Results 
🎯 COMPREHENSIVE TEST RESULTS - Enhanced ResNet-50 CNN
================================================================================
📊 Overall Pixel Accuracy:     0.9945 ± 0.0007
📊 Background Accuracy:        0.9981 ± 0.0003
----------------------------------------
OPTIC CUP (OC) METRICS:
  🔴 Dice Score:               0.8542 ± 0.0330
  🔴 Precision:                0.8035 ± 0.0541
  🔴 Recall:                   0.9136 ± 0.0176
  🔴 F1-Score:                 0.8542 ± 0.0330
----------------------------------------
OPTIC DISC (OD) METRICS:
  🟢 Dice Score:               0.8171 ± 0.0367
  🟢 Precision:                0.7564 ± 0.0589
  🟢 Recall:                   0.8914 ± 0.0038
  🟢 F1-Score:                 0.8171 ± 0.0367
----------------------------------------
COMBINED OC + OD METRICS:
  🏆 Mean Dice Score:          0.8356 ± 0.0093
  🏆 Mean Precision:           0.7799 ± 0.0098
  🏆 Mean Recall:              0.9025 ± 0.0088
  🏆 Mean F1-Score:            0.8356 ± 0.0093
<img width="2442" height="3989" alt="image" src="https://github.com/user-attachments/assets/b63e6cb6-bd5c-4c52-a8e7-c9f8aae96c12" />

<img width="636" height="658" alt="image" src="https://github.com/user-attachments/assets/80abe546-5441-4708-8694-66e88267b3c7" />

