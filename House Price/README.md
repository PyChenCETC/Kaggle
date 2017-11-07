# House Prices: Advanced Regression Techniques
[House Prices: Advanced Regression Techniques@Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

> 作者：周振宇  
> 邮箱：blue_liberty@qq.com

## [建模过程](http://nbviewer.jupyter.org/github/blueliberty/Kaggle/blob/master/House%20Price/code/House%20Prices%EF%BC%9AAdvanced%20Regression%20Techniques.ipynb)
+ 载入必要的库
+ 机器学习框架
+ 初识数据集
+ 探索性数据分析
	+ 相关系数矩阵
	+ 单变量分析
		+ SalePrice
		+ 其他变量
	+ 双变量分析
		+ 连续型变量
		+ 离散型变量
+ 特征工程
	+ 异常值
	+ 对房屋价格进行log变换
	+ 缺失值
	+ 合并训练集和测试集
	+ 对有序的离散型变量进行编码
	+ 房屋总面积变量
	+ Box-Cox 变换
	+ 对无序的离散型变量进行独热编码
	+ 分离训练集和测试集
+ 建模
	+ 交叉验证函数
	+ 基模型
+ 模型融合
	+ 简单平均融合
	+ 堆叠模型
	+ 加权平均融合

## 最终结果
![](https://raw.githubusercontent.com/blueliberty/Kaggle/master/House%20Price/FinalResult.png)