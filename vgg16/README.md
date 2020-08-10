# VGG16_pytorch

Dataset
-------
#### Cat vs Dog dataset Download Site : <https://www.kaggle.com/c/dogs-vs-cats/data>
Train dataset을 Train iamge 17000장, vaildation image 4000장, test image 4000장으로 나누어서 실험하였다.(그림1 참조)   
   
>그림1   

<img src="/vgg16/image/1.JPG" width="80%" height="80%" title="img1" alt="img1"></img>

VGG Architecture
----------------
<img src="/vgg16/image/2.JPG" width="80%" height="80%" title="img2" alt="img2"></img>
***

Option
------
#### torch version : 1.4
#### input_shape : [224,224,3], Batch_size : 16 , epoch 5 
#### compile option : optimizers= 'SGD(lr = 0.001, momentum=0.9)', loss= nn.BCELoss()

Result
------
<img src="/vgg16/image/3.JPG" width="80%" height="80%" title="img3" alt="img3"></img>
