# Deep_Neural_Networks_From_Scratch
Timeline and files in implementing DNN from scratch

## File Description

* 00- v1.0 - Data preparation file
* 01- v1.1 - Logistic Regression and 2 Layer Shallow Neural Network (sigmoid -> sigmoid)
* 02- Data augmentation (increasing dataset, thus creating new dataset)
* 03- v1.1.1 v1.1 with new dataset
* 04- v1.2 shallow nn implementation (relu -> sigmoid) on original dataset
* 05- v1.2.1 v1.2 with new dataset (relu -> sigmoid)
* 06- v1.3 deep nn with original dataset ((n-1)relu -> sigmoid)
* 07- v1.3.1 deep nn with new dataset
* 08- v1.3.2 v1.3.1 with He/Xavier initialization and Dropout regularization (failed)
* 09- v1.3.3 v1.3.1 with He/Xavier Initialization
* 10- v1.4 DNN with He/Xavier initialization and Adam optimizer
* 11- v_1.1   3 classes instead of 2,
* 12- v_1.1.1 softmax function changed
* 13- v_1.2   uses adam optimizer 
* 14- v_1.2.1 now 7 classes,with adam optimizer

- - - 

| File No.   | Training Accuracy | Testing Accuracy |
| ---------- | ----------------- | ---------------- |
| 01 (logistic)     | 100 %             | 73.77 %            |
| 01 (shallow) | 100 %             | 78 % |
| 03 (logistic) | 100 % | 68.59 % |
| 03 (shallow) | 100 % | 67 % |
| 04 | 100 % | 75.41 % |
| 05 | 99.99 % | 81.81 % |
| 06 | 100 % | 73.77 % |
| 07 | 99.9 % | 74.38 % |
| 08 (for 2 layers) | 98.76 % | 76.86 % |
| 08 (for 4 layers,failed) | -- | -- |
| 09 | 99.22 % | 74.38 % |
| 10 | 99.05 % | 79.12 % |
| 11 | 38.9 % | 35.64 % |
| 12 | 95.52 % | 61.69 % |
| 13 | 64.63 % | 53.23 % |
| 14 | 100 % | 32.11 % |

- - - 
Dataset from -
[Dog Dataset](https://www.kaggle.com/jessicali9530/stanford-dogs-dataset)

Code Snippets from

[Course1](https://www.coursera.org/learn/neural-networks-deep-learning)

[Course2](https://www.coursera.org/learn/deep-neural-network)

[Master Course](https://www.coursera.org/specializations/deep-learning)

Inspired by - 
[Andrew Ng](https://www.linkedin.com/in/andrewyng/)

