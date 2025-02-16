# ML-Attacks-Defenses

### Dataset
The project was done using two datasets , MNIST and Brain Tumor Classification Dataset. 
MNIST Dataset : Handwritten Digits 
* 10 classes
* 60,000 – training samples, 
* 10,000 – testing samples
Brain Tumor Classification Dataset
* 4 Different Classes - Glioma_tumor, meningioma_tumor, no_tumor, pituitary tumor
* 394 – testing samples
* 2870 – training samples

### Victim Model 
The victim model implemented is a simple DNN built with Sequential API. With MNIST the training Accuracy is 98% and testing Accuracy: 97% and with brain tumor dataset the training Accuracy is 99% and testing Accuracy 73%

### Attacks and Defenses
#### Attacks
* BIM ( Basic Iterative Method)
* PGD (Projected Gradient Descent)
* JSMA (Jacobian-based Saliency Map Attack)
* C&W (Carlini & Wagner)
#### Defenses
* Feature Squeezing
* Defensive Distillation

### Output
![image](https://github.com/user-attachments/assets/40fbb9e2-673d-4ef6-80a5-63d5fa377c6f)




