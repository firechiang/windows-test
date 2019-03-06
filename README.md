##### windows相关命令
```bash
netstat -ano                                   # 列出所有端口占用情况
netstat -aon|findstr "8090"                    # 查看8090端口对应进程的PID  
tasklist|findstr "1280"                        # 查看进程PID"1280"被哪个程序占用
taskkill /pid "1280" -f                        # 杀死PID"1280"进程
taskkill /im Tencentdl.exe -f                  # 杀死Tencentdl.exe程序
```
