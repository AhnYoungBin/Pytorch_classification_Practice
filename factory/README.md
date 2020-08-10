# Cat vs Dog DataSet Factory

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
