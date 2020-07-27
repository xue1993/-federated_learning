# federated learning when only parts of the local updates are sent to the centeral server 

pytorch implement

the original code is from https://github.com/AshwinRJ/Federated-Learning-PyTorch (see for introduction and parameters setting）

## how to use it(still in trouble)
1.click the code file, then open all .ipynb in google colab. 
2.change the 'edit/notebook setting' to GPU
3.in the demo.ipynb, run command '%run federated_main.py'

## our revision includes：
newly options:
  --spr:Fraction of updates sent to the central server. Default is wowangle.
  --savefile:The default output is in the 'out.txt' created in the current path. 'a'.
save data path changed  
Code revision:
 the local updata

  
## our future work
1.change the models sent to the local devices to reduce the dim(see reference of selective SGD)
