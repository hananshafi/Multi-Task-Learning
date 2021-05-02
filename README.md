# Multi-Task-Learning
This repo contains code and exhaustive experiments on smart multi-task learning


## Model Architecture

![alt text](https://github.com/hananshafi/Multi-Task-Learning/blob/main/assets/mtl_model.jpg)

---

## Experiment 1


Data | Network details| Tasks | Task loss weights  | Regularization
---- | -------------- | ----- | ------------ | --------------- 
CIFAR-10 | 3-layered shared Network | Task a: cifar10 classes, Task b: animal vs non-animal,Task c: reconstruction | [1, 0.5, 1] | None

![alt text](https://github.com/hananshafi/Multi-Task-Learning/blob/main/assets/exp1loss.png)

---

## Experiment 2


Data | Network details| Tasks | Task loss weights  | Regularization
---- | -------------- | ----- | ------------ | --------------- 
CIFAR-10 | 3-layered shared Network | Task a: cifar10 classes, Task b: animal vs non-animal,Task c: reconstruction | [1, 0.5, 1] | single Dropout layer (0.2)

![exp 2](https://github.com/hananshafi/Multi-Task-Learning/blob/main/assets/exp_2_paint.jpg)

---

## Experiment 3


Data | Network details| Tasks | Task loss weights  | Regularization
---- | -------------- | ----- | ------------ | --------------- 
CIFAR-10 | 3-layered shared Network | Task a: cifar10 classes, Task b: animal vs non-animal,Task c: reconstruction | [0.5, 0.1, 1] | Dropout layer (0.2) after each Conv layer

![exp 3](https://github.com/hananshafi/Multi-Task-Learning/blob/main/assets/exp_3.jpg)

---

## Experiment 4


Data | Network details| Tasks | Task loss weights  | Regularization
---- | -------------- | ----- | ------------ | --------------- 
CIFAR-10 | 2-layered shared Network | Task a: cifar10 classes, Task b: animal vs non-animal,Task c: reconstruction | [0.5, 0.1, 1] | Dropout layer (0.2)

![exp 4](https://github.com/hananshafi/Multi-Task-Learning/blob/main/assets/exp_4.jpg)

---


## Experiment 5


Data | Network details| Tasks | Task loss weights  | Regularization
---- | -------------- | ----- | ------------ | --------------- 
CIFAR-10 | 3-layered shared Network | Task a: cifar10 classes, Task b: animal vs non-animal,Task c: reconstruction, Task d: random binary task | [0.5,0.1,1,0.1] | Dropout layer (0.2) after each Conv layer

![exp 5](https://github.com/hananshafi/Multi-Task-Learning/blob/main/assets/exp_5.jpg)

