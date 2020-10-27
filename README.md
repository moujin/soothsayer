Neural Network for Time Series Prediction.  
Using the PyTorch to predict time series steps and sequences. Includes  stock market data.  
Support LSTM,Bidirectional LSTM and so on model.     

使用PyTorch实现的神经网络预测时间序列数据包括股市数据   



模型预测能力如何？  
模型在多长时间后预测能力失效？  
模型包括   LSTM和Bidirectional LSTM   
如果您想加入自己的模型需要在model文件夹中增加您自己的神经网络        

运行方法  
训练  
python main.py -p "train" -m 2  

预测  
python main.py -p "predict" -m 2  

参数说明  
-m 表示  
1:LSTM  
2:BidirectionalLSTM  

如果要启动可视化  
命令行运行 python -m visdom.server  
在浏览器输入 http://localhost:8097  

预测结果  
蓝色是真实数据  
橙色是预测数据  
结果如下图所示  
![](figure/predict_high.png)

