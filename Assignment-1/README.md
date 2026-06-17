# Emotion Recognition Using Audio Features

## Spectral Features 

![angry.png](images/angry.png)
![happy.png](images/happy.png)
![sad.png](images/neutral.png)
![neutral.png](images/sad.png)

### BaseLines

| Model                 |  Accuracy  |    UAR     | Macro F1-score |
|:----------------------|:----------:|:----------:|:--------------:|
| **Neural Net**        | **32.04%** | **31.78%** |   **31.82%**   |
| **Random Forest**     | **32.04%** |   31.43%   |     30.16%     |
| **Linear SVM**        |   29.28%   |   28.38%   |     27.28%     |
| **AdaBoost**          |   28.73%   |   31.05%   |     28.43%     |
| **Naive Bayes**       |   28.18%   |   31.29%   |     21.26%     |
| **RBF SVM**           |   27.07%   |   27.07%   |     10.65%     |
| **Decision Tree**     |   23.76%   |   20.94%   |     19.47%     |
| **Nearest Neighbors** |   23.76%   |   14.20%   |     11.34%     |

## Self-Supervised Approach

| Model        | Accuracy |  UAR   | Macro F1-score |
|:-------------|:--------:|:------:|:--------------:|
| **wav2vec2** |  27.07%  | 25.00% |     10.65%     |
| **data2vec** |  25.41%  | 25.00% |     10.23%     |

![wav2vec2.png](images/wav2vec5.png)
![data2vec.png](images/data2vec5.png)

| Model        | Accuracy |  UAR   | Macro F1-score |
|:-------------|:--------:|:------:|:--------------:|
| **wav2vec2** |  27.07%  | 25.00% |     10.65%     |
| **data2vec** |  25.41%  | 25.00% |     10.23%     |

![wav2vec2.png](images/wav2vec10.png)
![data2vec.png](images/data2vec10.png)

## References

1. https://scikit-learn.org/stable/auto_examples/classification/plot_classifier_comparison.html
