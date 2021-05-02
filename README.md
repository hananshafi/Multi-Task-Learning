# Multi-Task-Learning
This repo contains code and exhaustive experiments on smart multi-task learning


## Model Architecture

![alt text](https://github.com/hananshafi/Multi-Task-Learning/blob/main/assets/mtl_model.jpg)

---

## Experiment 1


Data | Network details| Tasks | Task loss weights  | Regularization | Approx. Total_loss
---- | -------------- | ----- | ------------ | --------------- 
CIFAR-10 | 3-layered shared Network | Task a: cifar10 classes, Task b: animal vs non-animal,Task c: reconstruction | [1, 0.5, 1] | None | Train_Loss: 0.2414, Val_Loss: 2.3439

![alt text](https://github.com/hananshafi/Multi-Task-Learning/blob/main/assets/exp1loss.png)

---

## Experiment 2


Data | Network details| Tasks | Task loss weights  | Regularization | Approx. Total_loss
---- | -------------- | ----- | ------------ | --------------- 
CIFAR-10 | 3-layered shared Network | Task a: cifar10 classes, Task b: animal vs non-animal,Task c: reconstruction | [1, 0.5, 1] | single Dropout layer (0.2) | Train_Loss: 0.2515, Val_Loss: 1.5522

![exp 2](https://github.com/hananshafi/Multi-Task-Learning/blob/main/assets/exp_2_paint.jpg)

---

## Experiment 3


Data | Network details| Tasks | Task loss weights  | Regularization | Approx. Total_loss
---- | -------------- | ----- | ------------ | --------------- 
CIFAR-10 | 3-layered shared Network | Task a: cifar10 classes, Task b: animal vs non-animal,Task c: reconstruction | [0.5, 0.1, 1] | Dropout layer (0.2) after each Conv layer | Train_Loss: 0.2395, Val_Loss: 0.4353

![exp 3](https://github.com/hananshafi/Multi-Task-Learning/blob/main/assets/exp_3.jpg)

---

## Experiment 4


Data | Network details| Tasks | Task loss weights  | Regularization | Approx. Total_loss
---- | -------------- | ----- | ------------ | --------------- 
CIFAR-10 | 2-layered shared Network | Task a: cifar10 classes, Task b: animal vs non-animal,Task c: reconstruction | [0.5, 0.1, 1] | Dropout layer (0.2) | Train_Loss: 0.4399, Val_Loss: 0.6924 

![exp 4](https://github.com/hananshafi/Multi-Task-Learning/blob/main/assets/exp_4.jpg)

---


## Experiment 5


Data | Network details| Tasks | Task loss weights  | Regularization | Approx. Total_loss
---- | -------------- | ----- | ------------ | --------------- 
CIFAR-10 | 3-layered shared Network | Task a: cifar10 classes, Task b: animal vs non-animal,Task c: reconstruction, Task d: random binary task | [0.5,0.1,1,0.1] | Dropout layer (0.2) after each Conv layer | Train_Loss: 0.2746, Val_Loss: 0.5267

![exp 5](https://github.com/hananshafi/Multi-Task-Learning/blob/main/assets/exp_5.jpg)

