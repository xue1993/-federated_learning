# federated learning when only parts of the local updates are sent to the centeral server 

pytorch implement

the original code is from https://github.com/AshwinRJ/Federated-Learning-PyTorch (see for introduction and parameters setting）

## how to use it(still in trouble)
0.open your notebook, like jupter/google colab
1.download/git clone the repo in local computer or google drive
2.change the 'edit/notebook setting' to GPU  
3.open demo.ipynb in google, reset the path
4.run command '%run federated_main.ipynb'
5.upload the output in save folder 

## our revision includes：
newly options:
  --spr:Fraction of updates sent to the central server. Default is wowangle.
  --savefile:The default output is in the 'out.txt' created in the current path. 'a'.
save data path changed  
Code revision:
 the local updata

  
## our future work
1.change the models sent to the local devices to reduce the dim(see reference of selective SGD)
