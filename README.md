# unix_common_cmd

#### #check unix version  
```$uname -a```
#### #check cpuinfo(file under /proc)
```$cat /proc/cpuinfo```
#### #list all processes
```$ps aux```
##### #sort 
(https://stackoverflow.com/questions/7880784/what-is-rss-and-vsz-in-linux-memory-management)
###### #by rss
```$ps aux --sort -rss```
###### #by vsz
```$ps aux --sort -vsz```
##### #easy way use top
```$top```
#### #check system current memory usage(https://www.linuxnix.com/find-ram-size-in-linuxunix/)
```$free```
