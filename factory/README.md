# Cat vs Dog DataSet Factory


## Training
```
! python3 /content/ex/main.py -h
```
```
modelnum list
------------------------------
1: Vgg11
2: Vgg13
3: Vgg16
4: Vgg19
5: Resnet18
6: Resnet34
7: Resnet50
8: Resnet101
9: Resnet152
10:DenseNet121
11:DenseNet169
12:DenseNet201
13:DenseNet161(growth_rate = 48)
------------------------------
usage: main.py [-h] [-se] [-show] modelnum lr epochs

Learn by Modeling Dog Cat DataSet

positional arguments:
  modelnum    Select your model number
  lr          Select opimizer learning rate
  epochs      Select train epochs

optional arguments:
  -h, --help  show this help message and exit
  -se         Put the selayer in the model.
  -show       show to model Archtecture
```


## GradCAm
```
! python3 /content/ex/grad.py '/content/gdrive/My Drive/dataset/test/cat/cat.1.jpg' 5 '/content/gdrive/My Drive/model/test_resnet18ep2001e5_pytorch.pth'
```
```
modelnum list
------------------------------
1: Vgg11
2: Vgg13
3: Vgg16
4: Vgg19
5: Resnet18
6: Resnet34
7: Resnet50
8: Resnet101
9: Resnet152
10:DenseNet121
11:DenseNet169
12:DenseNet201
13:DenseNet161(growth_rate = 48)
------------------------------
usage: grad.py [-h] [-se] path modelnum state_dict_path

show GradCAM

positional arguments:
  path             image path
  modelnum         Select your model number
  state_dict_path  Select your model number

optional arguments:
  -h, --help       show this help message and exit
  -se              Put the selayer in the model.
  ```
  
  ```
  ! python3 /content/ex/grad.py '/content/gdrive/My Drive/dataset/test/cat/cat.1.jpg' 5 '/content/gdrive/My Drive/model/test_resnet18ep2001e5_pytorch.pth'
  ```
<img src="/factory/image/gradcam.png" width="80%" height="80%" title="img1" alt="img1"></img>   
  
