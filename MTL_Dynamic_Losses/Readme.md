# Dynamic Loss Weighting schemes


---

## Weighting by Uncertainity
(Multi-task learning using uncertainty to weigh losses for scene geometry and semantics. Kendall et al., CVPR 2018)

![alt text](https://github.com/hananshafi/Multi-Task-Learning/blob/main/MTL_Dynamic_Losses/assets/loss.JPG)


Data     | Cifar10 weight | Animal_vs_Non-Animal weight | Reconstruction weight
-------- | -------------- | ----------------------- | -------------------------  
CIFAR-10 |    0.9062182   |       2.1785831         |   0.811066

![alt text](https://github.com/hananshafi/Multi-Task-Learning/blob/main/MTL_Dynamic_Losses/assets/combined_stats.jpg)


---

## Dynamic Weight Averaging
( End-to-End Multi-Task Learning with Attention, Shikun Liu et al., CVPR 2019)

![alt text](https://github.com/hananshafi/Multi-Task-Learning/blob/main/MTL_Dynamic_Losses/assets/dwa_1.JPG)
![alt text](https://github.com/hananshafi/Multi-Task-Learning/blob/main/MTL_Dynamic_Losses/assets/dwa_2.JPG)


Data     | Cifar10 weight | Animal_vs_Non-Animal weight | Reconstruction weight
-------- | -------------- | ----------------------- | -------------------------  
CIFAR-10 |    0.7590300976534575   |       1.4041971145200465         |   0.8367727878264959

![alt text](https://github.com/hananshafi/Multi-Task-Learning/blob/main/MTL_Dynamic_Losses/assets/combined_dwa_stats.jpg)

