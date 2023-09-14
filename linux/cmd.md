

查看当前系统各个进程产生了多少旬柄
lsof -n |awk '{print $2}'|sort|uniq -c |sort -nr|more


查看各连接状态的计数情况
netstat -n |awk '/^tcp/ {++S[$NF]} END {for (a in S) print a, S[a]}'
