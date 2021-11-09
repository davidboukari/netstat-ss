# netstat-ss

## netstat
```
sudo netstat -tunlp

The options used in this command have the following meaning:

    -t - Show TCP ports.
    -u - Show UDP ports.
    -n - Show numerical addresses instead of resolving hosts.
    -l - Show only listening ports.
    -p - Show the PID and name of the listener’s process. This information is shown only if you run the command as root or sudo user.
```

## ss (statistic socket)
* https://www.cyberciti.biz/tips/linux-investigate-sockets-network-connections.html
```
ss -lntpu
```
