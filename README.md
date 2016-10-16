Time machine and shutdown
==============================
2016-10-16


Launch time machine then shut your mac in one line.



This script starts a time machine backup, and when done, it shuts down your mac.


```bash
sudo tmutil startbackup --block;
sudo shutdown -h now;
exit
```


I personally make a tmdown alias for it, which makes it very easy to backup the pc before going to bed.
