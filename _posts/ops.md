```bash
//监控硬件
yum -y install OpenIPMI ipmitool
ipmitool sdr type Temperature

lscpu、uptime、top、htop vmstat mpstat //cpu相关

vmstat 2 1 //每2秒采样 采一次样
uptime //可显示运行时间和负载 如遇问题 负载不高 可能由于网络引起问题
```

```powershell
copype amd64 x:\PE
MakeWinPEMedia /ISO x:\PE x:\PE\PE.iso

diskpart
list volume
Mount-DiskImage -StorageType ISO -Access ReadOnly -ImagePath
```

