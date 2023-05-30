# 该项目是一个利用现有的原始数据进行简单加工适合于机器学习文白翻译的数据集项目

# 项目结构

## 1. 项目目录结构

项目创建日期为文件夹名

## 2. 项目数据结构

以Date0525(1)为例

    {

        "name": "魏书_列传_卷七",

        "with_punctuation": "景穆皇帝十四男。",

        "translation": "景穆皇帝有十四个儿子。"

    },

### 处理原则:

包含文白对照两个字段，其中`with_punctuation`字段为原始文本，`translation`字段为翻译文本，`name`字段为原始文本的出处。

### 处理方法:
参考 https://github.com/Hellohistory/PrepPro 处理脚本


# 3. 项目数据来源
https://github.com/BangBOOM/Classical-Chinese

https://github.com/NiuTrans/Classical-Modern

# 4. 项目更新历史
## 2023-05-30 项目创建，并上传两个项目数据集

Date0524当中一共包含26个JSON文件，总大小为242Mb

Date0525当中一共包含4670个JSON文件，总大小为99.4Mb