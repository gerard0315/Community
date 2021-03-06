# 监控区

监控区在K-Lab运行时的页面底部，分为日志监控和变量监控两个部分，用户可通过监控区右下角的按钮进行页面切换。在底部固定的监控条上可以看到K-lab的可用时间、CPU用量、内存用量、磁盘用量以及工作区用量。

![image description](/image/monitor-bar.png)

以下是注意事项：

**CPU用量：** 当CPU负载较高时，请耐心等待CPU运算，不要进行其他运算操作，否则Kernel可能会过载。

**内存用量：** 当内存占用了80%的时候，监控区会跳红，同时系统会触发提醒。在满负荷状态下，请尝试优化代码，提高运算效率，否则内存溢出可能导致Kernel崩溃重启。

**磁盘用量：** 磁盘是每次分配给用户的物理机的硬盘，可临时储存文件。当退出K-Lab，机器回收后，磁盘中的文件将不会被保存。当磁盘用量达到80%的时候将会跳红提醒，系统也会触发提示。需要特别注意的是，如果使用超出了磁盘用量，可能会触发防止恶意行为的惩罚机制，用户会被强制退出K-Lab，并且无法申请到计算资源。若发生该情况请及时通过页面右下角意见反馈按钮联系管理员。

**工作区：** 与磁盘不同，工作区是一个500MB的云端持久化存储空间，存储在其中的文件可持久化保存。但如果用量超出500MB，之后的文件将不会被保存。当工作区用量达90%的时候，监控区也会出现提示，请密切关注。

## **日志监控**

用户可以通过查看系统日志的方式来分析运行过程中的异常信息。

![image description](/image/log-monitor.png)

## **变量监控**

在变量监控区，可以随时查看项目的变量赋值情况，显示的信息有：变量名、类型、占用内存和变量的赋值。

![image description](/image/variable-monitor.png)



