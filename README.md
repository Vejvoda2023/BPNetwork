# BP神经网络项目集

## 项目概览
本项目集包含三个基于BP神经网络的分类任务，分别针对乳腺癌诊断、信用卡欺诈检测和西瓜品质分类。

---

## 乳腺癌诊断

### 数据集
- 来源：sklearn.datasets.load_breast_cancer
- 特征：30个
- 类别：良性（0），恶性（1）

### 模型性能
```python
              precision    recall  f1-score   support

           0       0.95      0.77      0.85       167
           1       0.88      0.98      0.92       289

    accuracy                           0.90       456
   macro avg       0.91      0.87      0.89       456
weighted avg       0.90      0.90      0.90       456
```

### 项目结构
```
BreastCancerWisconsin/
├── BCW.ipynb        # 主程序文件
├── README.md        # 项目说明文档
```

---

## 信用卡欺诈检测

### 数据集
- 来源：creditcard.csv
- 特征：30个
- 类别分布：正常交易（284315条），欺诈交易（492条）

### 模型性能
- AUPRC：0.80
- 精确度：0.95（正常），0.88（欺诈）
- 召回率：0.77（正常），0.98（欺诈）

### 项目结构
```
CreditCardFraud/
├── CCF.ipynb        # 主程序文件
├── README.md        # 项目说明文档
├── AboutDataset.md  # 数据集说明文档
```

---

## 西瓜品质分类

### 数据集
- 来源：watermelon_3.csv
- 特征：密度、含糖率、纹理、敲声、色泽
- 类别：坏瓜（0），好瓜（1）

### 模型性能
```python
              precision    recall  f1-score   support

           0       1.00      1.00      1.00         2
           1       1.00      1.00      1.00         2

    accuracy                           1.00         4
   macro avg       1.00      1.00      1.00         4
weighted avg       1.00      1.00      1.00         4
```

### 项目结构
```
watermelon/
├── watermelon.ipynb        # 主程序文件
├── README.md               # 项目说明文档
```

---

## 通用信息

### 运行环境
- Python 3.x
- 依赖库：scikit-learn, numpy, pandas, matplotlib, seaborn

### 使用方法
1. 安装依赖：
```bash
pip install -r requirements.txt
```

2. 运行项目：
```bash
jupyter notebook <项目名称>.ipynb
```

### 许可证
MIT License

### 作者
[Vejvoda]
