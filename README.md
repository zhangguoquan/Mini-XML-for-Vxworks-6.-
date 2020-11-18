# Mini-XML-for-Vxworks-6.-

移植mini-xml3.2到vxworks 6.8

因为项目需要一个纯c的xml解析库，临时找了下，目前看来只有两个比较合适
一是ezxml库(http://ezxml.sourceforge.net/)
这个属于纯粹的源代码移植，后续再说
一个就是mini-xml库(https://www.msweet.org/mxml/)
目前最新版本是3.2

1 下载Mini-xml库

2  修改config.h.in 文件

     修改     #define MXML_VERSION 	"mini-xml v3.2"
     
     删除     #undef HAVE_PTHREAD_H
     
3  另存config.h.in为mxml-config.h 

4 打开 vxworks workbench

5 File>New>Wind River WorkBench Project

6 下一页选择 Wind River Vxworks 6.8  点击Next

7 选择Static Kernel Library 点击Next

8 填写项目名称，点击Finish

9 将下载的mxml文件下的文件（包括刚才修改的config.h文件)复制到刚建立的工程目录下

10 在工程下按F5刷新后，修改源文件中的#include “config.h” 修改为#include “mxml-config.h”

11 在工程处右键选择属性在Build Properties 选择build tools 在Active Build spec中选择SIMNTgnu（对应的平台，这里用vxsim）

12 选择build 就生成了对应的.a静态库文件

13 以后工程中（DKM工程或者VIP工程)使用包含.a静态库文件，mxml-config.h 文件，mxml-private.h文件以及 mxml.h文件就可以了





