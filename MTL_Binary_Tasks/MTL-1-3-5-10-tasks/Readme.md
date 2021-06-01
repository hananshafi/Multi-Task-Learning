# MTL - Performance comparison with multiple tasks on CIFAR100 dataset

![alt text](https://github.com/hananshafi/Multi-Task-Learning/blob/main/MTL_Binary_Tasks/MTL-1-3-5-10-tasks/assets/Network_cifar100.jpg)

---

## Single Task Accuracies

Task-1 Accuracy | Task-2 Accuracy  | Task-3 Accuracy | Task-4 Accuracy | Task-5 Accuracy 
--------------- |  ---------------- | --------------- | --------------- | ---------------
Val_Acc: 0.839 |  Val_Acc: 0.775   |  Val_Acc: 0.738 |  Val_Acc: 0.722 | Val_Acc: 0.714

---

## MTL Accuracies

### 3 Task Network

       Task-1 accuracies = [ 0.842 , 0.84 , 0.853 ]
       Mean Task-1 Accuracy = 0.845
       Standard Deviation (SD) = 0.0070
       --------------------------------------------
       Task-2 accuracies = [ 0.785 , 0.790 , 0.791 ]
       Mean Task-2 Accuracy = 0.789
       Standard Deviation (SD) = 0.00321
       --------------------------------------------
       Task-3 accuracies = [ 0.754 , 0.758 , 0.747 ]
       Mean Task-3 Accuracy = 0.753
       Standard Deviation (SD) = 0.0056

---

### 5 Task Network
      
       Task-1 accuracies = [ 0.839 , 0.834 , 0.83 ]
       Mean Task-1 Accuracy = 0.834
       Standard Deviation (SD) = 0.0045
       --------------------------------------------
       Task-2 accuracies = [ 0.788 , 0.777 , 0.789 ]
       Mean Task-2 Accuracy = 0.785
       Standard Deviation (SD) = 0.0066
       --------------------------------------------
       Task-3 accuracies = [ 0.755 , 0.749 , 0.754 ]
       Mean Task-3 Accuracy = 0.7526
       Standard Deviation (SD) = 0.00321
       --------------------------------------------
       Task-3 accuracies = [ 0.7416 , 0.733 , 0.736 ]
       Mean Task-3 Accuracy = 0.737
       Standard Deviation (SD) = 0.00436
       --------------------------------------------
       Task-3 accuracies = [ 0.744 , 0.741 , 0.731 ]
       Mean Task-3 Accuracy = 0.738
       Standard Deviation (SD) = 0.0068
       
---

### 10 Task Network

        Task-1 : 0.8355000019073486,
        Task-2 : 0.7760999798774719,
        Task-3 : 0.742900013923645,
        Task-4 : 0.73580002784729,
        Task-5 : 0.7372000217437744,
        Task-6 : 0.7289999723434448,
        Task-7 : 0.7522000074386597,
        Task-8 : 0.7264999747276306,
        Task-9 : 0.713699996471405,
        Task-10 : 0.7443000078201294
        
---

### Loss Visualizations

#### Sum of Losses

![alt text](https://github.com/hananshafi/Multi-Task-Learning/blob/main/MTL_Binary_Tasks/MTL-1-3-5-10-tasks/assets/loss_curves.png)


#### Average of Losses
![alt text](https://github.com/hananshafi/Multi-Task-Learning/blob/main/MTL_Binary_Tasks/MTL-1-3-5-10-tasks/assets/loss_curve_2.png)






      
      
       
       



