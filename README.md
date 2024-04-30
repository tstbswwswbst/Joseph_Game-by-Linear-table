# 新约瑟夫游戏的可视化实现C++
介绍：本项目是数据结构与C++程序设计课程的专题一大作业的汇总<br/>
专题目标：<br />
	（1）在实践中体会“对象”的使用方法，确定问题所涉及的类，确定每个类的属性和操作，完成对象之间的交互；<br />	
 	（2）掌握数据结构中线性表的顺序存储或者链式存储，实现基本操作，体会存储方式对应的优缺点<br />
# 目录：
## 1.题目要求
- ### 	 1.1 问题描述
	 设计一个“约瑟夫环”游戏模拟器，即n个人围成一圈，设置起点开始报数，按规定方向 1 、 2 、3 ......报数，<br />
	 当报数达到规定值（大于等于1的整数），则该人退出游戏，最后剩下的人为游戏胜利者。<br />
	 在基本游戏规则的基础上进行一些扩展，例如个人信息中包括密码（正负表示方向，数值表示报数规定值），游戏积分等。<br />
- ### 	 1.2 具体要求
	 编写一个“约瑟夫环”游戏模拟器。游戏者信息以一个人一条记录的形式存储，<br />
	 每个记录包含的信息有身份标识号（ID）、姓名、电话、电子邮箱、身份证号、密码、积分等信息。<br />
- ### 	 1.3 实现功能
	- 开户，若无账户，申请开户，提交必要的信息则可以开立游戏账户，ID由个人设定，密码随机生成，初始账户积分为零；
	- 查询，登录账户，选择查询功能，可以查看本人账户的全部信息；
	- 修改，登录账户，选择修改功能，可以修改电话或电子邮箱，其他信息不允许修改；
	- 游戏，登录账户，选择游戏功能，则全部账户参与游戏，按照开户顺序建立约瑟夫环，提供不同游戏模式 a. 简单 b. 中等 
		- a按照缺省的方向、规定值进行游戏；
		- b按照缺省的方向、规定值进行第一轮报数，当有人退出之后按照淘汰者的密码所指示的方向和报数值进行下一轮报数；
   	 	- 显示游戏过程，游戏发起者如果获得胜利则积分增加，如果失败则积分不变，参与者积分不变；
	- 销户，登录账户，选择销户功能，可以注销账户。
	- 浏览，登录系统，选择浏览功能，可获得当前账户的数量和积分排行榜；
	- 查找，登录系统，选择查找功能，可以查找指定账户，查看满足查找条件账户的公开信息；
	- 挑战，登录账户，选择挑战功能，游戏规则相同，积分规则改变为游戏发起者如果获得胜利则积分获得翻倍增加，如果失败则积分减少，参与者如果获得胜利则积分增加，如果失败则积分不变；
	- 文件的导入和保存，将账户信息表保存到文件，可导入和导出，当账户信息表发生添加、修改、删除后需要进行文件更新。
## 2.题目解读
## 3.代码实现
- ###  3.1 Version1：命令行实现全部游戏逻辑[Joseph-V1]
- ###  3.2 Version2：将命令行指令调整为可视化窗口[Joseph-V2]
- ###  3.3 Version3：约瑟夫游戏部分链表的可视化实现[Joseph-V3](zt1_Joseph\Joseph-V1)


