### 一、 google PageSpeed insight 钉钉报告工具介绍
该工具可以用于对web产品进行google PageSpeed insight检测，按照对于桌面设备和移动设备两个维度分别根据检测分数进行评级排名，然后在钉钉群里通报，通报样式如下：



### 二、实现思路
1.新建csv文件存放需要检测的产品信息，信息包括产品名，产品url,产品logo图片url

2.使用selenium 实现自动输入网址进行检测

3.保存检测检测结果截图于本地，并上传到github,返回图片URL

4.保存检测分数，并根据分数进行排序,评等级

5.使用钉钉机器人FeedCard消息类型接口，在钉钉群通报结果