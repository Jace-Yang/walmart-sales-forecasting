Processing文件夹原本是用来存放main.ipynb运行过程中产生的中间数据（由于数据过大电脑和服务器内存都有限制，必须分开进行），总共加起来有12.1GB，为了提交作业的时候方便老师下载。为了避免空的文件夹产生误会，我把中途的数据都替换成了空的同名pickle文件～

1. Features
- Basic Features: 存放**第一部分 1.**的基本特征
- Lags Features: 存放**第一部分 2.**的滞后阶特征
- Combined_FE: 存法**第一部分 3.**的聚合特征

2. Working_trained_models: 在**第二部分 2.模型训练**过程中，模型会把训练好的模型存储暂时储存，节省程序内存

3. Pretrained_models：储存并备份上一步训练好的模型，在预测的时候调用