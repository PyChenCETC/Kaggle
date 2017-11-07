# Titanic: Machine Learning from Disaster
[Titanic: Machine Learning from Disaster@Kaggle](https://www.kaggle.com/c/titanic)

> 作者：周振宇  
> 邮箱：blue_liberty@qq.com

## 建模过程
+ [FeaturePreprocessing](http://nbviewer.jupyter.org/github/blueliberty/Kaggle/blob/master/Titanic/code/FeaturePreprocessing.ipynb)
	+ 初步观察数据的状况
	+ 可视化描述性统计
	+ 初步特征工程
	+ 建立基线模型
	+ 进一步特征工程
+ [Modeling&FeatureSelection](http://nbviewer.jupyter.org/github/blueliberty/Kaggle/blob/master/Titanic/code/Modeling%26FeatureSelection.ipynb)
	+ 特征工程后的模型
	+ 特征选择
		+ 自编函数前向选择
		+ RFECV后向选择
		+ 在基线模型基础上，逐一加入或剔除新构建的特征
	+ 学习曲线
	+ 调参
	+ 过采样
+ [Logit_Svm](http://nbviewer.jupyter.org/github/blueliberty/Kaggle/blob/master/Titanic/code/Logit_Svm.ipynb)
	+ logistics模型
	+ SVM模型
+ [Ensemble](http://nbviewer.jupyter.org/github/blueliberty/Kaggle/blob/master/Titanic/code/Ensemble.ipynb)

## 最终结果
![](https://raw.githubusercontent.com/blueliberty/Kaggle/master/Titanic/FinalResult.png)