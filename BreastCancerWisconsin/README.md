# 乳腺癌诊断 - BP神经网络项目

## 项目概述
本项目使用BP神经网络对威斯康星州乳腺癌诊断数据集进行分类预测。通过构建多层感知器(MLP)模型，实现对乳腺癌的良恶性分类。

## 数据集
- 数据集来源：sklearn.datasets.load_breast_cancer
- 特征数量：30个
- 类别：
  - 0：良性
  - 1：恶性

## 模型性能
```python
              precision    recall  f1-score   support

           0       0.95      0.77      0.85       167
           1       0.88      0.98      0.92       289

    accuracy                           0.90       456
   macro avg       0.91      0.87      0.89       456
weighted avg       0.90      0.90      0.90       456