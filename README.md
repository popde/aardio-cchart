# aardio-cchart
在aardio中调用cchart.dll实现波形图/图表的显示与控制

首先介绍下这个图表:

CChart可以绘制多种二维、三维曲线，包括折线图、等高线图、云图、饼图、柱图、散点图、面积图、直方图、极线图、甘特图、雷达图、瀑布图、K线图，频谱图等，功能非常全面。 而且，CChart内部选项极为丰富，无论是曲线本身，还是标题、坐标轴、图例、背景、图像注释等部分，都有大量的选项可供设置，甚至消息响应、右键菜单等元素，都提供了自定义的方法。

CChart最大的优势，还是在于其对用户的友好性。在追求功能的同时，CChart在简化调用方面，做到了极致，一般只用几句代码就可以画出精致的图像。这一点可以说不仅胜过绝大部分非商业的图表软件，甚至不输于大部分商业图表软件。

CChart 开源免费, 支持MIT开源协议
CChart官方:http://www.cchart.net/

本代码是在cchartu.dll动态库上描述的aardio中使用方法
此 cchart.dll 可以通过$符号内嵌到exe里, 这样就可以生成完全绿色版独立exe了,使用波形图的时候不用释放dll到外部目录.
本文使用aardio编程软件 来自: http://www.aardio.com
本文首发于: https://www.htmlayout.cn/t/361

![image](https://github.com/popde/aardio-cchart/blob/main/demoImg/1587217901210547.png)
![image](https://github.com/popde/aardio-cchart/blob/main/demoImg/1587263218990628.png)
![image](https://github.com/popde/aardio-cchart/blob/main/demoImg/1587263941629636.png)
![image](https://github.com/popde/aardio-cchart/blob/main/demoImg/1587265009475984.png)
![image](https://github.com/popde/aardio-cchart/blob/main/demoImg/1587267345736640.png)
![image](https://github.com/popde/aardio-cchart/blob/main/demoImg/1587269417405629.png)
![image](https://github.com/popde/aardio-cchart/blob/main/demoImg/1587270630889436.gif)
![image](https://github.com/popde/aardio-cchart/blob/main/demoImg/1587271260249639.png)
![image](https://github.com/popde/aardio-cchart/blob/main/demoImg/1587271410791941.png)
![image](https://github.com/popde/aardio-cchart/blob/main/demoImg/1587271963359662.png)
