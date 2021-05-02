# Multi-Task-Learning
This repo contains code and exhaustive experiments on smart multi-task learning


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

![exp 2](https://github.com/hananshafi/Multi-Task-Learning/blob/main/assets/Untitled%20drawing(1).jpg)

---

## Experiment 3


Data | Network details| Tasks | Task loss weights  | Regularization
---- | -------------- | ----- | ------------ | --------------- 
CIFAR-10 | 3-layered shared Network | Task a: cifar10 classes, Task b: animal vs non-animal,Task c: reconstruction | [0.5, 0.1, 1] | Dropout layer (0.2) after each Conv layer

![exp 2](https://github.com/hananshafi/Multi-Task-Learning/blob/main/assets/Untitled%20drawing(1).jpg)

---

## Experiment 4


Data | Network details| Tasks | Task loss weights  | Regularization
---- | -------------- | ----- | ------------ | --------------- 
CIFAR-10 | 2-layered shared Network | Task a: cifar10 classes, Task b: animal vs non-animal,Task c: reconstruction | [0.5, 0.1, 1] | Dropout layer (0.2)

![exp 2](https://github.com/hananshafi/Multi-Task-Learning/blob/main/assets/Untitled%20drawing(1).jpg)

---


## Experiment 5


Data | Network details| Tasks | Task loss weights  | Regularization
---- | -------------- | ----- | ------------ | --------------- 
CIFAR-10 | 3-layered shared Network | Task a: cifar10 classes, Task b: animal vs non-animal,Task c: reconstruction, Task d: random binary task | [0.5,0.1,1,0.1] | Dropout layer (0.2) after each Conv layer

![exp 2](https://github.com/hananshafi/Multi-Task-Learning/blob/main/assets/Untitled%20drawing(1).jpg)

