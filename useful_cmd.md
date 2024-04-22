### 提取文件中间几行
sed -n '123,125p' merged_nodups.txt

### 查找某一命令的进程 ID，kill某任务
```
#列出进程ID
ps aux | grep "ssh -N -f -L localhost:8888"
#kill
kill 66824
```
