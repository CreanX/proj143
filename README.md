# proj143技术文档
搭建一个操作系统在线实验平台
## 参赛信息
赛题：在线操作系统实验平台

队名：重生之我在lgd扛大旗

成员：谢语诗 唐继堯 颜克耕

学校：中国人民解放军陆军工程大学

## 目标描述与完成情况
### 目标描述
Pintos教学操作系统（来自斯坦福大学CS140课程）存在环境搭建难、命令行调试操作不方便、实验项目规模大门槛高、无法进行在线实验等痛点，本项目开发一个原型系统对 Pintos进行调试环境图形化、实验项目任务化和实验平台在线化改造，实现实验项目智能测评。

基于以上内容，对项目目标进行拆分，我们需要在项目中完成以下功能：
|目标编号|目标内容|
|-|-|
|1|基于docker实现调试环境图形化|
|2|提出阶梯化任务式闯关实验项目体系的解决方案，实现内核实验智能测评|
|3|使用Moodle实现实验平台在线化访问，设计用于实验指导的在线问答系统|
|4|实现网络访问端口等资源分配和回收|
### 完成情况
|目标编号|完成情况|说明|
|-|-|-|
|1|已完成|基于docker实现调试环境图形化|
|2|已完成|提出阶梯化任务式闯关实验项目体系的解决方案，实现内核实验智能测评|
|3|已完成|使用Moodle实现实验平台在线化访问，设计用于实验指导的在线问答系统|
|4|未完成|实现网络访问端口等资源分配和回收|
|总计|完成度75％||
## 仓库文件简介
## 原型系统效果展示
## Pintos调试环境简介及问题
### 调试环境简介
Pintos是美国Stanford大学开发的一个基于80x86体系结构CPU的教学操作系统，它以比较简单的方式实现了内核线程、加载和运行用户程序等功能。Pintos操作系统可以直接运行在常规的采用80x86CPU的IBM兼容PC机上。不过为了实验和调试方便，我们通常在Linux系统上通过bochs仿真器运行pintos。

开发环境结构如下图所示：

![image](https://github.com/CreanX/proj143/assets/145346450/c62041e4-429f-4e2e-8ab0-8b71a3d5ae7f)

### 调试环境搭建
为满足日常的操作习惯，我们使用Windows平台虚拟机软件VMWare Workstation和源代码编辑工具SourceInsight，使pintos系统开发环境能运行于虚拟的Ubuntu系统之上。用户可以在Windows下使用SouceInsight对Pintos的代码进行分析和修改。同时，通过虚拟机软件VMWare 在Ubuntu下对修改后的代码进行编译链接、测试和调试。

**搭建平台**：Windows11、VMWare Workstation 17 pro、Ubuntu

**配套资源**：Ubuntu虚机映像文件MachineDing.zip和Pintos系统源代码文件DingShared.zip。

实验环境配置如下图所示：

![屏幕截图 2024-05-28 180755](https://github.com/CreanX/proj143/assets/145346450/dc3121e5-b58b-4578-a8e5-a2e4a9c2ceec)

pintos调试环境搭建需要以下步骤：

1. 安装VMware17
2. 解压资源文件MachineDing.zip和DingShared.zip
3. 导入Ubuntu虚机镜像
4. 共享解压后的DingShared.zip到虚拟机
5. 在Ubuntu终端测试编译
```
cd /mnt/hgfs/DingShared/pintos_workdir/pintos/src/threads/

make check
```

但仍存在调试环境搭建难、命令行调试不方便等问题。
## 改造思路
### 调试环境搭建难
### 命令行调试操作不方便
### 实验项目规模大完成门槛高
### 不能进行在线实验
## 方案设计与实现
### 实验环境及使用平台
### 基于GDBGUI 的调试环境搭建及可视化
### 实验项目任务化及智能测评
### 实验平台在线化
## 开发计划与工作重要进展
在本章节对开发过程中的项目重要进展进行总结，链接为项目开发对应的过程性技术文档
### 第一阶段
1.	安装docker，导入空白Ubuntu镜像
2.	配置操作系统实验环境，使基于GDBGUI的调试环境图形化
3.	制作镜像并导出，实现网页访问
### 第二阶段
拆分操作系统实验项目为三类任务：调试类、分析类、综合类，实现实验过程的数据采集与分析，同时实现内核实验智能测评。
1.	调试类
2.	分析类
3.	综合类
### 第三阶段
使用Moodle将实验任务集成，设计用于实验指导的在线问答系统，实现实验平台的多用户访问
### 第四阶段
1.	实现网络访问端口等资源分配和回收
2.	撰写技术文档
3.	项目提供可演示和试用的原型系统，初赛项目进入收尾阶段
## 开发中遇到的问题与解决方法
## 收获
