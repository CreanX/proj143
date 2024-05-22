# proj143
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
## 仓库文件简介
## 原型系统效果展示
## Pintos调试环境简介及搭建
## 改造思路
### 调试环境搭建难
### 命令行调试操作不方便
### 实验项目规模大完成门槛高
### 实验平台不能在线访问
## 方案设计与实现
### 项目总体方案（流程图）
### 基于GDBGUI 的调试环境搭建及可视化
### 实验项目任务化及智能测评
### 实验平台在线化
## 开发中遇到的问题与解决方法
## 收获
