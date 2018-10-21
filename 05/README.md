###  注意！！！
1、周末课程正常推进，助手酱除10点前发布课程外无法提供社群服务，答疑专家将在群内不定时答疑，请各位仔细阅读操作指导文档，感谢！

2、本轮代金券共计1500元，用于本次课程学习资源的购买，限制使用产品和时间，请大家不要购买其他产品，并仔细依照每天操作文档指导操作，如因您误操作造成的代金券不足，我们将无法补发，还请大家切记！切记！

------------------


# DAY5：图像识别介绍和应用

课程资料下载：
https://education.huaweicloud.com:8443/courses/course-v1:HuaweiX+CBUCNXE011+Self-paced/about

## 打卡任务：  

以上过程介绍了对URL图片添加标签的操作，可以再对SDK进行修改，使得将输入的URL修改为图片本地地址后，可以对本地图片添加图像标签。

### 3.1 修改代码，image_tagging_batch.py代码中第14行函数执行的是根据url获取图像，对其中urllib2.urlopen相应部分进行修改，使用open函数代替即可 (修改好的文件： )

### 3.2 运行以下命令将图片下载到本地（或用本地的其它图片）：
wget http://b.hiphotos.baidu.com/image/pic/item/a71ea8d3fd1f4134be1e4e64281f95cad1c85efa.jpg

### 3.3 运行以下命令对本地图片进行标签分析：
python image_tagging_batch.py a71ea8d3fd1f4134be1e4e64281f95cad1c85efa.jpg，得到结果如图所示，其中红框内是用户名，绿框内是图像标签：

### 3.4 打开Demo体验界面（http://image-demo.ei.huaweicloud.com/#/ais-demo/pc/image-tagging）,即可在线体验图像标签服务，可以与上述SDK得到的结果进行对照！

