最近在写Android连接服务器这一块，发现测试接口有点麻烦，便想着到网上找一找接口测试工具，找来找去我都不太满意。有些太精致，导致整个工具体积过大，打开要等好久，有些又太粗糙，连咋用都不知道，所以没办法，自己做一个吧，毕竟自己做的想如何设计都行。

于是我用Java的Swing做了一个窗体小工具，专门用来测试接口。
工具示例图：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190901160450510.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibGl6emF3YW5nLmJsb2cuY3Nkbi5uZXQ=,size_16,color_FFFFFF,t_70)

包含几种常见的请求方式，还可以设计请求的参数、头信息，参数也可以指定数据类型，例如json、xml等等，下面可以返回对应的内容和头信息。
初步计划是这个样子，不过后面我会考虑再加点元素进去，好让工具的功能丰富些，把它放在桌面，即开即用，非常方便。

使用示意图：

![在这里插入图片描述](https://img-blog.csdnimg.cn/20190901160840570.gif)

有需要的小伙伴可以下载玩一玩，或者用来测试接口，界面简陋了一点，也请大家见谅。后面我会继续改进。
源码已上传至GitHub：
https://github.com/blizzawang/InterfacnTestingTool.git

**觉得不错请给个star支持一下，谢谢！**
