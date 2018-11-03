今天答疑专家：@姜娜 @西北偏北 @for @TcD   

本轮代金券共计1500元，用于本次课程学习资源的购买，限制使用产品和时间，请大家不要购买其他产品，并仔细依照每天操作文档指导操作，如因您误操作造成的代金券不足，我们将无法补发，还请大家切记！切记！   

------------------
# Day 18 华为云深度学习技术起底   

课程资料下载：     
https://education.huaweicloud.com:8443/courses/course-v1:HuaweiX+CBUCNXE011+Self-paced/courseware/5e29ca6e51f64744bad4633355b108b1/35d3a9ba418b4c1da0701998b4553c5c/

打卡任务：     
截图1：利用深度学习完成模型训练及部署，学习文档中有成功部署示例截图。         
截图2：利用postman向深度学习发起预测请求，获得预测结果如文档示例图片。    


# FAQ:

### 1、样本数据地址：https://obs.cn-north-1.myhwclouds.com/dls-public-common-data/hc2018/data/hands-on-lab/huawei.dls.hc2018.handsonlab.data.zip     

### 2、src对应训练数据集文件路径，dst对应切分后数据的输出路径，训练集使用切分后的eval/train里面的。确保训练数据集目录下包含train和eval文佳夹

### 3、作业参数模型名称：resnet_v1_50

### 4、上传模型失败，请确保桶路径里面有模型文件

### 5、TensorBoard 报错的问题，请确保路径选择的是训练输出的路径，并保证里面有模型文件

### 6、由于现在使用的人较多，所以在创建训练作业的时候，资源需要排队，创建的时间会慢些, 建议优先选择cpu规格

### 7、预测作业的模型路径与训练作业的文件输出路径保持一致，接口类型为restful

### 8.postman 图片预测时body的key为images不要漏了s，若还是无结果输出去掉content＿type参数试试，复制token时不能有多余的空格

### 9. 分类结果logits代表了每个类别的得分，得分越高，对应类别的可能性越大，类别对应标签可以去训练作业的日志最前面查看

### 10. from
moxing.tensorflow.datasets.raw.raw_dataset import
split_image_classification_dataset

注意from … import split…在一行中


-----


https://obs.cn-north-1.myhwclouds.com/dls-public-common-data/hc2018/data/hands-on-lab/huawei.dls.hc2018.handsonlab.data.zip    


![](https://raw.githubusercontent.com/latermonk/AI_21DAY/master/18/PNG/DAY1801.jpg)
![](https://raw.githubusercontent.com/latermonk/AI_21DAY/master/18/PNG/DAY1802.jpg)

