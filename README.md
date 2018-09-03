# 这是什么项目？
这是一个可以与“黄金点”游戏服务器交互的示例客户端程序，使用 C# + [WPF](https://docs.microsoft.com/en-us/dotnet/framework/wpf/) 实现。
这个客户端提供了基本的游戏功能，比如控制游戏的进程、提交黄金点、查看历史提交数据、游戏房间管理等。

效果如下图：
![Sample image](/sample.PNG)

# 什么是“黄金点”游戏？
请在邹欣老师的博客查看游戏介绍：[创新的时机 – 黄金点游戏](https://blog.csdn.net/SoftwareTeacher/article/details/25794525)

## 我们采用的游戏规则
N个玩家，每人写一个或两个0~100之间的有理数 (不包括0或100)，提交给服务器，服务器在当前回合结束时算出所有数字的平均值，然后乘以0.618（所谓黄金分割常数），得到G值。提交的数字最靠近G（取绝对值）的玩家得到N分，离G最远的玩家得到－2分，其他玩家得0分。只有一个玩家参与时不得分。

# 我们需要哪些预备知识来阅读这些代码？
为了阅读这部分代码，我们需要：
- 对 C# 编程语言有基本的了解；
- 对 C# 的 `async/await` 编程模式有基本的了解。

同时，这些知识能更好地帮助理解这些代码：
- 对多线程操作的基本认识；
- 对 `Task`-based 异步操作的理解。
- 对 WPF 和 XAML 的了解。

# 如何让这个项目在机器上跑起来呢？
为此，我们需要：
- Windows 操作系统；
- Visual Studio 2017（推荐[免费的 Community 版本](https://visualstudio.microsoft.com/zh-hans/vs/community/)），并安装 ***.NET桌面开发*** 工作负载。

aaaaaa
