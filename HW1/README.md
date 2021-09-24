# HW 1

**Objective**: Implement contrastive representation learning with SimCLR on small dataset.

**Build with**:
* _**Pytorch**_ (1) 
* _**Tensorflow**_ (2) 

![](image_aug_sample.png)

**Techniques applied**:
* **Image Augmentation (Random Crop/Resize/Color Distortion)** 
* **ResNet18 and ResNet50**
* **Contrastive Loss (NT-XEnt)**
* **ReLU Activation Layer**
* **TSNE Visualization** 

**Lowest Loss Achieved**:
* **Pytorch**
    - SimCLR: Randomly select 10k training data + extra 30k augmented, Batch Size = 3, Number of Epoch = 100, Temperature = 0.1
    - Linear Model with Non-linear Projection (Train Acc = % , Testing Acc = % )
* **Tensorflow**
    - SimCLR: Randomly select 10k training data + extra 30k augmented, Batch Size = 3, Number of Epoch = 100, Temperature = 0.1
    - Linear Model with Non-linear Projection (Train Acc = % , Testing Acc = % )

Reference/Modified code from the following notebooks: 
* https://medium.com/analytics-vidhya/understanding-simclr-a-simple-framework-for-contrastive-learning-of-visual-representations-d544a9003f3c
* https://github.com/sayakpaul/SimCLR-in-TensorFlow-2

