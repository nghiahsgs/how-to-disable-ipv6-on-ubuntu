# how-to-disable-ipv6-on-ubuntu
how to disable ipv6 on ubuntu


```
ip a
```

```
sudo sysctl -w net.ipv6.conf.all.disable_ipv6=1
sudo sysctl -w net.ipv6.conf.default.disable_ipv6=1
sudo sysctl -w net.ipv6.conf.lo.disable_ipv6=1
```

```
ip a
```
