# CS405 Machine Learning - 课程实验仓库

> ⚠️ 学术诚信声明  
> 本仓库包含南方科技大学机器学习课程（CS405）的实验练习与作业模板，仅供学习参考。  
> 请勿将仓库内容直接用于课程作业提交。

## 项目简介

本仓库用于整理 CS405 课程的实验内容，覆盖从 Python 基础、数据预处理到朴素贝叶斯与线性回归的入门实践。仓库中同时包含中文与英文版本的部分 Notebook，便于双语学习。

## 目录结构

```text
LICENSE
README.md
lab/
    lab01/
        HelloWorld.py
        standardplot.py
        practice/
            practice/
                numpy_practice_zh.ipynb
                numpy_practice.ipynb
                python_practice_zh.ipynb
                python_practice.ipynb
                pythonpractice_test_cases/
    Lab02.Preliminary/
        census.csv
        load_loans.csv
        whatiswrong.py
        Lab02_Assignment_Template_zh.ipynb
        Lab02_Assignment_Template.ipynb
        Lab02_Preliminary_zh.ipynb
        Lab02_Preliminary.ipynb
        images/
    Lab03.Naïve-Bayes/
        Lab3.Naïve-Bayes_zh.ipynb
        Lab3.Naïve-Bayes.ipynb
        ling-spam/
            train-mails/
            test-mails/
        images/
    Lab04.Linear Regression/
        Lab04.pdf
        Lab4-Linear-Regression.ipynb
        cal_housing_py3.pkz
        housing.csv/
            housing.csv
        images/
```

## 环境准备

建议使用 Python 3.10 及以上版本，并通过虚拟环境隔离依赖。

```bash
python -m venv .venv

# Windows PowerShell
.venv\Scripts\Activate.ps1

# macOS / Linux
source .venv/bin/activate

pip install numpy pandas matplotlib seaborn scikit-learn scipy jupyter notebook
```

## 实验内容概览

1. Lab01：Python 基础、NumPy 练习、可视化入门。
2. Lab02：数据读取、清洗、探索、特征预处理与基础建模。
3. Lab03：朴素贝叶斯方法与邮件垃圾分类数据实践。
4. Lab04：线性回归基础与房价数据集实验。

### Lab04 数据说明（最新）

- 课程作业当前可使用老师提供的 `cal_housing_py3.pkz` 数据集。
- 在 `Lab4-Linear-Regression.ipynb` 中建议采用“训练集 + 验证集 + 测试集”流程，并在训练集上做交叉验证。
- 测试集仅用于最终一次评估，避免数据泄漏。

## 使用方式

### 运行脚本

```bash
cd lab/lab01
python HelloWorld.py
python standardplot.py
```

### 启动 Notebook

```bash
jupyter notebook
```

启动后在浏览器中打开对应实验目录下的 .ipynb 文件。

### Lab04 作业建议运行位置

```bash
cd "lab/Lab04.Linear Regression"
jupyter notebook
```

进入 `Lab4-Linear-Regression.ipynb` 后，优先确认 `cal_housing_py3.pkz` 文件与 Notebook 位于同一目录。

## 维护说明

README 的更新规范见根目录文件 README_UPDATE_REQUIREMENTS.md。

## 学术诚信

1. 可以参考仓库内容理解课程概念与代码实现。
2. 可以学习代码组织方式与实验流程。
3. 不得直接复制仓库内容作为课程作业提交。

## 许可证

本项目采用 [MIT License](LICENSE)。

最后更新：2026-03-20
