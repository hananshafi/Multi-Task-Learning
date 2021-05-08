# MTL - Single Task Baseline Models



---

## CIFAR10 Baseline


Data     | Network details | Regularization | Approx. Accuracy | Approx. Loss
-------- | ----------------- | -------------- | -----------------  | -------------
CIFAR-10 | Conv Layers: 3, Dense: 1 | Dropout (0.2) | Train_Acc: 0.8527, Val_Acc: 0.7418 | Train_Loss: 0.4114, Val_Loss: 0.7509

![alt text](https://github.com/hananshafi/Multi-Task-Learning/blob/main/single-task-baselines/assets/cifar_10.jpg)

---

## Animal vs Non-Animal Baseline


Data     | Network details | Regularization | Approx. Accuracy | Approx. Loss
-------- | ----------------- | -------------- | -----------------  | -------------
CIFAR-10 | Conv Layers: 3, Dense: 1 | Dropout (0.2) | Train_Acc: 0.9872, Val_Acc: 0.9477 | Train_Loss: 0.0339, Val_Loss: 0.1640

![exp 2](https://github.com/hananshafi/Multi-Task-Learning/blob/main/single-task-baselines/assets/an_vs_non-an.png)

---

## Reconstruction Baseline I


Data     | Network details         | Regularization | Approx. Loss
-------- | ----------------------- | -------------- | ----------------- 
CIFAR-10 | standard 3-layered encoder-decoder, num_filters=[8,16,32], latent=32 | Dropout (0.2) encoder |  Train_Loss: ~ 0.010, Val_Loss: ~ 0.012

![exp 3](https://github.com/hananshafi/Multi-Task-Learning/blob/main/single-task-baselines/assets/recon_base_I.png)

---

## Reconstruction Baseline II


Data     | Network details         | Regularization | Approx. Loss
-------- | ----------------------- | -------------- | ----------------- 
CIFAR-10 | standard 3-layered encoder-decoder, num_filters=[8,16,32], latent=16 | Dropout (0.2) encoder |  Train_Loss: ~ 0.016, Val_Loss: ~ 0.017

![exp 3](https://github.com/hananshafi/Multi-Task-Learning/blob/main/single-task-baselines/assets/recon_base_II.png)

---


## Reconstruction Baseline III


Data     | Network details         | Regularization | Approx. Loss
-------- | ----------------------- | -------------- | ----------------- 
CIFAR-10 | standard 2-layered encoder-decoder, num_filters=[8,16], latent=8 | Dropout (0.2) encoder |  Train_Loss: ~ 0.022, Val_Loss: ~ 0.023

![exp 3](https://github.com/hananshafi/Multi-Task-Learning/blob/main/single-task-baselines/assets/recon_base_III.png)

---

## Reconstruction Baseline IV


Data     | Network details         | Regularization | Approx. Loss
-------- | ----------------------- | -------------- | ----------------- 
CIFAR-10 | standard 2-layered encoder-decoder, num_filters=[4,8], latent=8 | Dropout (0.2) encoder |  Train_Loss: ~ 0.023, Val_Loss: ~ 0.023

![exp 6](https://github.com/hananshafi/Multi-Task-Learning/blob/main/single-task-baselines/assets/recon_base_IV.png)

---

## Reconstruction Baseline V


Data     | Network details         | Regularization | Approx. Loss
-------- | ----------------------- | -------------- | ----------------- 
CIFAR-10 | standard 2-layered encoder-decoder, num_filters=[16,32], latent=32 | Dropout (0.2) encoder |  Train_Loss: ~ 0.010, Val_Loss: ~ 0.012


![exp 6](https://github.com/hananshafi/Multi-Task-Learning/blob/main/single-task-baselines/assets/recon_base_V.png)

---

## Reconstruction Baseline VI


Data     | Network details         | Regularization | Approx. Loss
-------- | ----------------------- | -------------- | ----------------- 
CIFAR-10 | standard 3-layered encoder-decoder, num_filters=[8,16,32], latent=32, Batch normalization | Dropout (0.2) encoder-decoder |  Train_Loss: ~ 0.015, Val_Loss: ~ 0.025


![exp 6](https://github.com/hananshafi/Multi-Task-Learning/blob/main/single-task-baselines/assets/recon_base_VI.png)

### Sample reconstructed images
    Model: 2-layered, num_filters=[16,32], latent = 32
    
   ![exp 6](https://github.com/hananshafi/Multi-Task-Learning/blob/main/single-task-baselines/assets/reconstructed_images.png)
    

