# hw07
hw07/
├── train.ipynb        # 完整代码+输出
├── requirements.txt
├── README.md
├── report.md           # 作业报告
└── figures/
    ├── loss_acc.png
    └── confusion_matrix.png
    ## 运行环境
- Kaggle Notebook
- Python 3.9+
- GPU：开启

## 数据集
- 挂载：Add Data → 搜索 Chest X-Ray Images (Pneumonia)
- 路径：/kaggle/input/chest-xray-pneumonia/chest_xray

## 运行方式
1. 打开 train.ipynb
2. 直接运行所有 cell
3. 结果输出：figures/ 曲线 + 混淆矩阵

## 依赖
见 requirements.txt

## 测试指标
- Acc: 0.94 | Precision: 0.93 | Recall: 0.97 | F1: 0.95
