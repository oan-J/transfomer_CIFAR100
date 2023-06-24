# transformer-cifar100

Vision Transformer训练方法：
Train :
```bash
python train.py -c configs/default.yaml --name 模型名字
```
测试方法
Test :
```bash
python test.py -c configs/defaul.yaml --name 模型名字 -p 导入的模型的位置
```
<!-- 
Resnet训练方法：
train:
```bash
python train.py -net resnet50 -gpu
```
test：
```bash
python test.py -net resnet50 -weights 导入的模型的位置 -gpu
``` -->

You can find .event files in 'log/model' dir.

可下载训练好的模型进行测试
模型下载地址：https://drive.google.com/drive/folders/1GTRAt-JTgsFZj1HL6C8RqX1ksItvAYTp
