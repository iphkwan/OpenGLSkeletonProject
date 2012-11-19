OpenGLSkeletonProject
=====================

这是我的计算机图形学课程利用OpenGL实现人体动作模拟的作业。

=====================
开发环境：Microsoft Visual Studio 2010

附OpenGL工具包的配置:
	Step.1. 自行在网上下载GLUT工具包，并解压。
	Step.2. 将工具包中的头文件“gl.h”、“glu.h”、“glut.h”和“glaux.h”放到目录C:\Program Files\Microsoft SDKs\Windows\v7.0A\Include\gl下（开发环境vs2010安装于C盘下）。
	Step.3. 将库文件“gl.lib”、“glu.lib”、“glut.lib”和“glaux.lib”放到目录：C:\Program Files\Microsoft SDKs\Windows\v7.0A\Lib下。
	Step.4. 把解压得到的动态链接文件“glut.dll”和“glut32.dll”放到操作系统目录下面的system32文件夹内。
	Step.5. 在vs建项后，项目->属性->链接器->输入->“附加依赖项”，加入“glut.lib”等条目。

=====================

程序中的可控操作：
	1. 移动鼠标：改变视角
	2. "a"键：向左转（逆时针旋转）
	3. "d"键：向右转（顺时针旋转）

=====================
最后特别感谢zonyitoo同学(https://github.com/zonyitoo)提供技术指导及相关代码参考。
