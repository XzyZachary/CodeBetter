Dynamic Programming总结

     1.确定dp数组（dp table）以及下标的含义

     2.确定递推公式

     3.dp数组如何初始化

     4.确定遍历顺序

     5.举例推导dp数组

思路基本：
  * 状态转移，碰到类似的题目，万物先创建一个DP二维数组，最好的办法就是画格子
![WX20221215-155919](https://user-images.githubusercontent.com/16535001/207804735-1fd027e8-5d3b-46b9-9003-a87cbdddb748.png)



数组 滑动窗口

![209 长度最小的子数组](https://user-images.githubusercontent.com/16535001/207811731-013775b9-a7ec-46dc-9c79-40d900a306c7.gif)

大概思路：个人感觉是 暴力循环的一种优化，while遍历，如果大于目标值了，就平移下一个，实现了跳到下一个循环，然后找到符合条件的值
