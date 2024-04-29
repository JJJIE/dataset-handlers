# Dataset-Handlers

### 各种用于处理图像数据的小脚本


### Data_mask
> 给图像增加随机数量和大小的黑色正方形遮挡  
> 目前设置的是5个方块，每个方块大小为50*50  
>  
> block_size = 50  # 方块大小  
> num_blocks = 5  # 方块数量  
>   
> 1. 划定范围： 
>    在图像右边和下边减去方块的边长作为随机点的取值范围  
> 2. 在范围中随机取方块数量的点
> 3. 以点为左上角，向右向下画方块


### Dataset_classify
> 将数据集随机分成测试集和训练集  
> 同时每3000个文件划分一个文件夹
>   
> images_per_folder = 3000  
> 
> 文件夹的名字以’aa‘开始‘zz‘结束  
> 其中训练集占总图像数量的80%  
>   
> train_ratio = 0.8  


### Mapping
> 生成索引  



### add_channal
> 将一张jpg作为新的通道添加到png图片中  
> 使得png图像拥有四个通道  


### analyze
> 检查通道数，并输出各个通道  


### move
> 移动指定数量的文件到另一个文件夹  
> （或者复制过去）  


