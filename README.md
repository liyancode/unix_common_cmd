# unix_common_cmd

#### #check unix version  
```$uname -a```
#### #check cpuinfo(file under /proc)
```$cat /proc/cpuinfo```
#### #list all processes
```$ps aux```
##### #sort 
(http://www.commandlinefu.com/commands/view/3/display-the-top-ten-running-processes-sorted-by-memory-usage)
(https://stackoverflow.com/questions/7880784/what-is-rss-and-vsz-in-linux-memory-management)
###### #by rss
```$ps aux --sort -rss```
###### #by vsz
```$ps aux --sort -vsz```
##### #easy way use top
```$top```
#### #check system current memory usage(https://www.linuxnix.com/find-ram-size-in-linuxunix/)
```$free```
#### #quick back to pre visit directory
```$cd -```
