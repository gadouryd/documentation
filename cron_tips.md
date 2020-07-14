# Run command every 10s

`crontab -e`

* * * * * date; ps aux | grep "capsule8-sensor" | grep -v "root" >> /var/log/c8-metrics.log
* * * * * sleep 10; date; ps aux | grep "capsule8-sensor" | grep -v "root" >> /var/log/c8-metrics.log
* * * * * sleep 20; date; ps aux | grep "capsule8-sensor" | grep -v "root" >> /var/log/c8-metrics.log
* * * * * sleep 30; date; ps aux | grep "capsule8-sensor" | grep -v "root" >> /var/log/c8-metrics.log
* * * * * sleep 40; date; ps aux | grep "capsule8-sensor" | grep -v "root" >> /var/log/c8-metrics.log
* * * * * sleep 50; date; ps aux | grep "capsule8-sensor" | grep -v "root" >> /var/log/c8-metrics.log
© 2020 GitHub, Inc.
