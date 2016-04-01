# RJSearchNetTool
这是我基于AFNetWorking3.0封装的检查网络环境的工具类，很方便。 
使用方法：将我的文件夹拖入你的项目中，导入"RJSearchNetTool.h"头文件，即可使用。
+ (void)searchnet;开始检测，可以自定义在方法中做事情。
但是请记住，在delloc方法中一定要调用【RJSearchNetTool stopSearch】方法。
