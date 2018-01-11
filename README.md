# lnkskiller
1kb lnks Virus Killer for Windows

最近交期末实验报告频繁去学校文印店打印，去一次中一次毒，根目录下全部文件变成快捷方式，太忙也没想去管。
昨晚才去仔细观察了一下根目录，发现文件都被加了隐藏和系统属性，还有一个隐藏的VB脚本。
用批处理杀完恢复文件后发现病毒会再生。
用netstat -noab | findstr scipt命令找到对应进程kill掉后再执行批处理成功消灭。
重新把过程理了一遍写入lnkskiller.bat。
不过忘了备份病毒……更新后的批处理还没重新测试，理论上可行。
