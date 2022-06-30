# Jittor_question_one

## 简介
jittor风景图片生成赛，赛题将会提供1000张测试分割图片，参赛选手需要根据测试图片生成符合标签含义的风景图片。

## Requirements

```
jittor
pillow
opencv-python
```
## 安装 
```
git clone https://github.com/Jittor/gan-jittor.git
pip install -r requirements.txt
```

#### 运行环境
- ubuntu 20.04 LTS
- python >= 3.7
- jittor >= 1.3.0

## 数据集下载
```
#训练集
wget https://cloud.tsinghua.edu.cn/f/1d734cbb68b545d6bdf2/?dl=1
#测试集
wget https://cloud.tsinghua.edu.cn/f/70195945f21d4d6ebd94/?dl=1
```
目录结构为
```
train
|---images
|---labels # 训练集
|---label # 测试集
|---license.ch.txt
|---license.en.txt
```
## Train

单卡训练
```
bash runoob.sh
```

## 致谢
此项目代码参考了 [jittor-gan](https://github.com/Jittor/gan-jittor)。
