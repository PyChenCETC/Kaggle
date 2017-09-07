# 提交的预测结果文件及说明

benchmark，线上得分0.78469

rf0\_fs\_prediction，随机森林基线模型，前向选择特征，交叉验证0.828276，线上得分0.79426

gbm0\_fs\_prediction，GBM基线模型，前向选择特征，交叉验证0.836179，线上得分0.78469

xgb0\_fs\_prediction，XGBoost基线模型，前向选择特征，交叉验证0.837278，线上得分0.78947

rf0\_rfecv\_addfeature\_prediction，随机森林基线模型，后向选择特征，交叉验证0.82271，线上得分0.77033

rf0\_prediction，随机森林基线模型，手工选择特征，交叉验证0.82606，线上得分0.78947

rf0\_addsex\_prediction，随机森林基线模型，手工选择特征（增加Sex_encode特征），交叉验证0.8238258，线上得分0.79426

gbm0\_prediction，GBM基线模型，手工选择特征，交叉验证0.8305989，线上得分0.77512

xgb0\_prediction，XGBoost基线模型，手工选择特征，交叉验证0.8350366，线上得分0.76555

rf\_tuning\_prediction，随机森林调参模型，手工选择特征，交叉验证0.831672，线上得分0.78947

rf\_tuning\_classweight\_prediction，随机森林调参过采样模型，手工选择特征，交叉验证0.831672，线上得分0.78947

gbm0，线上得分0.78469

pred，线上得分0.78469

ensemble，线上得分0.79426

ensemble1，线上得分0.79904

ensemble2，线上得分0.79426

ensemble3，线上得分0.79904