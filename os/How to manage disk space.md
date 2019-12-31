# How to manage disk space

* Check file-system

```
➜  ~ df
Filesystem     1K-blocks    Used Available Use% Mounted on
overlay         61278020 9374276  48761296  17% /
tmpfs              65536       0     65536   0% /dev
tmpfs            2997936       0   2997936   0% /sys/fs/cgroup
shm                65536       0     65536   0% /dev/shm
/dev/sda1       61278020 9374276  48761296  17% /root/Dropbox
tmpfs            2997936       0   2997936   0% /proc/asound
tmpfs            2997936       0   2997936   0% /proc/acpi
tmpfs            2997936       0   2997936   0% /proc/scsi
tmpfs            2997936       0   2997936   0% /sys/firmware
```
    df -h #--human-readable

* Check disk usage

    du | sort -h
    du -h --threshold=100M | sort -h

## More
