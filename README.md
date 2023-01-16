Log4netRemotingServerService  
============================

Clone of https://hg.codeplex.com/log4netremotelogging


[![Build status](https://ci.appveyor.com/api/projects/status/toxap17lvenq8yl4/branch/master?svg=true)](https://ci.appveyor.com/project/emrah/log4netremotingserverservice/branch/master)


6.安装服务

用.net framework工具INSTALLUTIL安装服务程序即可。

用项目的输出作为参数，从命令行运行 InstallUtil.exe。在命令行中输入下列代码： 
installutil.exe  目录：C:\Windows\Microsoft.NET\Framework\v4.0.30319    路径   必需用管理员打开CMD
installutil yourproject.exe

Hint: a windows service must first be installed using installutil.exe and then started with the serviceExplorer, windows Services Administrative tool or the NET START command.

 

7.卸载服务

用项目的输出作为参数，从命令行运行 InstallUtil.exe。

installutil /u yourproject.exe
