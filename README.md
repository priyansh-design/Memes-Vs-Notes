# Memes-Vs-Notes
## Architecture (Non-Conv)
(Numpy)
Dense Layer - C(256x256x3,1000)   
Dense Layer - C(1000,50)  
Dense Layer - C(50,1)   


learning_rate = 0.01  

**Accuracy**
Training Set (1000/1600) - 72.6%  
Validation Set (300/1600) - 90%

(PyTorch)
Dense Layer - C(256x256x3,1000)   
Dense Layer - C(1000,50)  
Dense Layer - C(50,2)   

Optimizer - ADAM
learning_rate = 0.001  

**Accuracy**
Training Set (1000/1600) - 99.6%  
Validation Set (300/1600) - 90.33%

![alt text](https://github.com/priyansh-design/Memes-Vs-Notes/blob/main/download.png)

## Architecture (Conv)
Training set-1500/1600
Validation set-80/1600
Test set-20/1600

F - Filter, S - Stride, C - Channels   
Conv Layer - F(11x11) S(4x4) C(3,96)  
Conv Layer - F(5x5) S(4x4) C(96,132)  
Max Pool - F(2x2) S(2x2)   
Conv Layer - F(3x3) C(132,158)   
Max Pool - F(2x2) S(2x2)  
Dense - C(158x2x2,252)   
Dense - C(252,2)   

Optimizer - ADAM   
learning_rate = 0.001   
batch size-50

epoch size for both training and validation set-5

**Accuracy**
Training Set (1500/1600) - 95%   
Validation Set (80/1600) - 95%


Data is at
https://drive.google.com/drive/u/0/folders/1ntSQMw7P1ZModZW8qDaleEvUDTlmd7kL


## To open the Colab Notebooks
Goto - https://colab.research.google.com/github/
and then copy and paste the notebook links from the repository