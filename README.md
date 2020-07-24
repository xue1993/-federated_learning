# federated learning when only parts of the local updates are sent to the centeral server 

pytorch implement

the original code is from https://github.com/AshwinRJ/Federated-Learning-PyTorch（see for introduction and parameters setting）

## our revision includes：
options:
  --spr:Fraction of updates sent to the central server. Default is wowangle.
  
## our future work
1.change the models sent to the local devices to reduce the dim(see reference of selective SGD)
