# AutoControl
**[中文](https://github.com/georgel2020/Default/blob/main/README-CN.md) [English](https://github.com/georgel2020/Default/blob/main/README.md)**
> 一个**小巧便携**的应用程序，它能控制你的**鼠标和键盘**，这样能帮助你**更快捷地**执行操作。
## 特点
- 自动快速完成所有的任务。
- 自己决定执行的操作列表。
- 支持不同类型性的命令。
- 小巧便携。
## 指南
- 在`AutoControl.txt`中输入指令。以下的功能是被支持的，并附上样例：
  - `leftclick x y` （在坐标*x*, *y*单击鼠标左键。）
  - `leftdoubleclick x y` （在坐标*x*, *y*双击鼠标左键。）
  - `rightclick x y` （在坐标*x*, *y*单击鼠标右键。）
  - `keyclick n` （在键盘上按下*n*键。使用虚拟键值的整数形式。）
  - `sleep t` （等待*t*毫秒。）
  - `return` （结束所有操作。一般情况下，这在文档末尾是必要的。）
  - 未完待续……
```
rightclick 278 426
sleep 100
leftclick 434 646
sleep 100
leftclick 543 568
sleep 100
doubleclick 270 451
sleep 200
keyclick 65
sleep 1000
return
```
- 打开程序并等待直到所有操作完成。
- 点击[这里](https://docs.microsoft.com/zh-cn/windows/win32/inputdev/virtual-key-codes)查看虚拟键值对照表。使用调试程序获取鼠标实时位置。
## 截图
![image](https://user-images.githubusercontent.com/86717650/169291191-8c280cf6-0a92-4271-82fb-64391f01ab90.png)
## 版权
该应用程序全部由*George Lin*制作。
