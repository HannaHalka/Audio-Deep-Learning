# Solve the Audio Classification

Dataset contains 106800 observations and only 1950 unique patient. 

![img.png](images/distribution.png)


**CNN** \
![img.png](images/cnn_loss.png)

**resnet50** \
![img.png](images/resnet50.png)

**resnet18** \
![img.png](images/resnet18.png)

| Model (MFCC)   | Accuracy |  UAR   | Macro F1-score |          Competition          |
|:---------------|:--------:|:------:|:--------------:|:-----------------------------:|
| **Custom CNN** |  39.97%  | 40.65% |     40.15%     | ![img.png](images/error1.png) |
| **resnet50**   |  37.63%  | 37.12% |     37.11%     |                               |
| **resnet18**   |  34.21%  | 33.37% |     32.95%     |                               |
