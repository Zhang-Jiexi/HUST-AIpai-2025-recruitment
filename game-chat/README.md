---
configs:
- config_name: default
  data_files:
  - path: game_chat_train.jsonl
    split: train
  - path: game_chat_validation.jsonl
    split: validation
- config_name: subset
  data_files:
  - path: game_chat_train_100.jsonl
    split: train
  - path: game_chat_validation_100.jsonl
    split: validation
license: Apache License 2.0
---

数据集文件元信息以及数据文件，请浏览“数据集文件”页面获取。

当前数据集卡片使用的是默认模版，数据集的贡献者未提供更加详细的数据集介绍，但是您可以通过如下GIT Clone命令，或者ModelScope SDK来下载数据集

#### 下载方法 
:modelscope-code[]{type="sdk"}
:modelscope-code[]{type="git"}



license: Apache License 2.0
text:
  text-classification:
    type:
      - multi-class
    language:
      - zh


## 数据集描述
数据集整体描述。

### 数据集简介
提供对于数据集的介绍，支持的使用场景（包括支持的语言等）。

### 数据集支持的任务
该数据集支持的训练任务，以及相关benchmark结果。


## 数据集的格式和结构

### 数据格式
对数据的格式进行描述，包括数据的schema，以及提供必要的数据样本示范。
如果数据集内含多个子数据集的话，每个字数据集都应该提供相对应的数据格式描述。


### 数据集加载方式
通过代码范例等方式，提供数据集通过MaaS/Dataset SDK进行加载和使用的详细说明。

### 数据分片
数据集是否进行了预分片（例如是否有预设的train/test/validation的数据分片）。
如果有，数据的分片时如何实现的。
如果没有预先分片，是否对于数据使用过程中的分片有什么推荐（比例等）。



## 数据集生成的相关信息

### 原始数据
描述原始数据的来源以及数据的初步收集是如何进行的，是否经过归一化等处理流程。

### 数据集标注
该数据集是否包含标注，若有的话，相关信息描述。

#### 标注过程
标注是通过什么方式实现的，流程如何。

#### 标注者
标注者相关信息，尤其是当标着和原始数据提供者有所区别时。



## 数据集版权信息

数据集相关的版权信息，授权使用的场景和用户。是否开源，以及采用哪个开源协议等等。

## 引用方式

数据集是否有相关联的文章，以及如果在研究论文中要引用该数据集是否有推荐的引用格式等等。

## 其他相关信息

该数据集可能包含的个人和敏感信息，使用数据集需要考虑的相关背景；
数据集可能包含的社会意义以及其中可能包含的bias信息和可能的局限性等等。