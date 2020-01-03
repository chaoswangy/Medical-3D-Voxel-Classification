Medical-3D-Voxel-Classification
=====
代码框架
-------
* [kerascompet](https://github.com/chaoswangy/Medical-3D-Voxel-Classification/blob/master/kerascompet.ipynb)
此程序为实现基于3D神经网络的医学图像分类的程序，包括读取数据，训练模型，输出结果，评估等
* [test](https://github.com/chaoswangy/Medical-3D-Voxel-Classification/blob/master/test.ipynb)
此程序为测试用的程序，修改读入数据和模型的地址后能够很快预测出评估的结果
* [my_model](https://pan.baidu.com/s/1veL5HXnQHByENuvNZWfVNw)
训练保存的模型，因为github上传有大小限制，所以上传到百度云，点击即可下载
----
修改地址说明
----
请将[test](https://github.com/chaoswangy/Medical-3D-Voxel-Classification/blob/master/test.ipynb)
中（第二个小模块）的<br>
* adress1设为储存所有训练集数据的地址（即储存所有训练用的`candidate.npz`的地址）<br>
* adress2设为储存训练集的二分类结果的地址（即存储`train_val.csv`的地址）<br>
* adress3设为储存所有测试集数据的地址（即储存所有测试用的`candidate.npz`的地址）<br>
* adress4设为储存模型的地址（即储存`my_model.h5`的地址）
-----
运行说明
------
准备好所有文件代码以及模型后，修改路径，运行程序[test](https://github.com/chaoswangy/Medical-3D-Voxel-Classification/blob/master/test.ipynb)
即可输出`Submission.csv`文件（即用于kaggle提交的），注意：该文件默认储存在`adress2`下（即存储train_val.csv的地址）<br>
如果要修改储存地址，可将test中第8个小模块中第13行中的'adress2'改为你想要输出的地址

------
另外，训练集和测试集数据以及训练集的二分类结果和自己预测的测试集的二分类结果不在上传。
