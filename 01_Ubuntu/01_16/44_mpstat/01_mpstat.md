# install mpstat
```{bash}
$ sudo apt-get install sysstat
```

# monitoring cpu's processors
```{bash}
$ mpstat -P ALL 5
Linux 4.4.0-131-generic (ubuntu)     10/10/2018     _x86_64_    (8 CPU)

04:36:01 PM  CPU    %usr   %nice    %sys %iowait    %irq   %soft  %steal  %guest  %gnice   %idle
04:36:06 PM  all   64.42    0.00    1.53    0.03    0.00    0.03    0.00    0.00    0.00   34.01
04:36:06 PM    0  100.00    0.00    0.00    0.00    0.00    0.00    0.00    0.00    0.00    0.00
04:36:06 PM    1   99.80    0.00    0.00    0.00    0.00    0.20    0.00    0.00    0.00    0.00
04:36:06 PM    2   99.80    0.00    0.20    0.00    0.00    0.00    0.00    0.00    0.00    0.00
04:36:06 PM    3   99.60    0.00    0.40    0.00    0.00    0.00    0.00    0.00    0.00    0.00
04:36:06 PM    4   18.40    0.00    2.40    0.00    0.00    0.00    0.00    0.00    0.00   79.20
04:36:06 PM    5   41.24    0.00    2.99    0.00    0.00    0.00    0.00    0.00    0.00   55.78
04:36:06 PM    6   34.80    0.00    3.20    0.20    0.00    0.00    0.00    0.00    0.00   61.80
04:36:06 PM    7   21.53    0.00    3.02    0.00    0.00    0.00    0.00    0.00    0.00   75.45
```
