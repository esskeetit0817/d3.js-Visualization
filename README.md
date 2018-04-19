# 概要
棒球数据集包含根据惯用手分组的棒球运动员的中位数统计。每一组数据都包含惯用手、身高、体重、平均得分值、全垒打计数。
可视化图表分别解释了基于棒球运动员惯用手分类的得分情况和身高、体重度量。




图1（惯用手和得分情况）：

![image.png](https://upload-images.jianshu.io/upload_images/9246628-7b535dd1b9fd3d46.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

左手球员具有较高的全垒打和平均得分率。

图2（惯用手和身体指标）：

![image.png](https://upload-images.jianshu.io/upload_images/9246628-74cb49daed00ee5a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
双手击球的球员体重较轻，身高较低。



# 设计
利用python对棒球数据进行分析，得到两个结论：
1.惯用手为双手的人，体重偏轻，身高偏矮。
2.惯用手为左手的人，击球率和全垒得分较高。
进而制作两张图表展示结论.  

x轴作为离散变量表示惯用手,y轴采用双坐标轴反应两个连续变量.

图表的形式：柱状图/散点图.



# 反馈和迭代
index1.html:               

反馈：柱子太粗,导致交互不清晰.
改进一:尝试制作分组柱状图,但是柱子本身是冗余信息,只保留柱子顶端即可.然后发现气泡图效果更好.


index2.html:                  
反馈：标题不居中,数据概括性介绍,表名和结论太少.
改进二:标题居中,增加元素进行数据来源说明和分析概括.增加第二张图表，以便将得分情况、身体指标与惯用手的关系分来来讲。


index3.html:                 
反馈：两张图表色彩一样,应加以区分.
改进三:使用assignColor改变图表颜色,选择色彩柔和及无障碍视觉颜色.



# 资源

http://dimplejs.org/examples_viewer.html?id=bubbles_vertical_lollipop                     
http://bl.ocks.org/asawong/54b95818ca76b3c5a5cdc359d05b1d4e                      
https://highsounding.github.io/                          
http://www.d3noob.org/
