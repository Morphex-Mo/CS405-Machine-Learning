# CS405 Machine Learning - 课程实验

> **⚠️ 学术诚信声明**  
> 本仓库包含南方科技大学机器学习课程（CS405）的实验作业和练习代码，仅供学习参考。  
> **请勿直接抄袭代码用于课程作业提交，违者后果自负。**

## 📚 课程简介

本仓库存储了机器学习课程的实验代码和练习材料，涵盖了机器学习的基础概念、数据处理、模型训练等内容。

## 📂 项目结构

```
lab/
├── lab01/                          # 实验一：Python基础与可视化
│   ├── HelloWorld.py               # Python基础示例
│   ├── standardplot.py             # Matplotlib绘图示例
│   └── practice/                   # 练习文件夹
│       └── practice/
│           ├── numpy_practice.ipynb    # NumPy练习
│           ├── python_practice.ipynb   # Python练习
│           └── pythonpractice_test_cases/  # 测试用例
│
└── Lab02.Preliminary/              # 实验二：数据预处理与初步分析
    ├── Lab02_Preliminary.ipynb         # 实验指导笔记本
    ├── Lab02_Assignment_Template.ipynb # 作业提交模板
    ├── whatiswrong.py                  # 调试练习
    ├── census.csv                      # 人口普查数据集
    ├── load_loans.csv                  # 贷款数据集
    └── images/                         # 图片资源
```

## 🔧 环境配置

### 依赖库

本项目使用 Python 3.x，主要依赖以下库：

- **NumPy**: 数值计算和矩阵运算
- **Pandas**: 数据处理与分析
- **Matplotlib**: 数据可视化
- **Seaborn**: 统计数据可视化
- **Scikit-learn**: 机器学习算法库
- **SciPy**: 科学计算

### 安装方法

```bash
# 创建虚拟环境（推荐）
python -m venv .venv

# 激活虚拟环境
# Windows
.venv\Scripts\activate
# Linux/Mac
source .venv/bin/activate

# 安装依赖
pip install numpy pandas matplotlib seaborn scikit-learn scipy jupyter
```

## 📖 实验内容

### Lab 01 - Python基础与可视化
- Python 基础语法练习
- NumPy 数组操作
- Matplotlib 数据可视化
- 基础绘图示例

### Lab 02 - 数据预处理与初步分析
- 数据加载与探索（`pandas`）
- 数据清洗与预处理
- 特征工程基础
- 标准化与归一化（`StandardScaler`, `MinMaxScaler`）
- 数据可视化分析
- 简单机器学习模型（逻辑回归、决策树）

## 🚀 运行方式

### 运行 Python 脚本

```bash
cd lab/lab01
python HelloWorld.py
python standardplot.py
```

### 运行 Jupyter Notebook

```bash
jupyter notebook
# 然后在浏览器中打开相应的 .ipynb 文件
```

## 📝 注意事项

1. **数据文件路径**: 代码使用相对路径加载数据文件，确保从正确的目录运行脚本
2. **调试练习**: `whatiswrong.py` 包含数据分析的示例代码，用于学习数据探索方法
3. **作业模板**: `Lab02_Assignment_Template.ipynb` 是作业提交模板，请按要求完成

## 🎓 学习资源

- [Scikit-learn 官方文档](https://scikit-learn.org/)
- [Pandas 官方文档](https://pandas.pydata.org/)
- [NumPy 官方文档](https://numpy.org/)
- [Matplotlib 官方文档](https://matplotlib.org/)

## 📄 许可证

本项目采用 [MIT License](LICENSE) 开源协议。

**版权声明**: 本仓库代码为个人学习成果，仅供参考。使用本代码时请遵守学术诚信原则。

## ⚖️ 学术诚信

本仓库的代码和材料仅供学习和参考使用。如果你是正在修读此课程的学生：

- ✅ 可以参考代码理解概念和方法
- ✅ 可以学习代码风格和编程技巧
- ❌ 不得直接复制粘贴代码作为作业提交
- ❌ 不得在不理解的情况下使用代码

请记住：**抄袭违反学术诚信，损害的是你自己的学习成果。**

---

*最后更新: 2026年3月*
