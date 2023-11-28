>UFW, or Uncomplicated Firewall, is a simplified firewall management interface that hides the complexity of lower-level packet filtering technologies such as iptables and nftables.

### Check Firewall status

```
sudo ufw status
```

### Disable it

```
sudo ufw disable
```

### Enable it

```
sudo ufw enable
```

### Reset all firewall rules

```
sudo ufw reset
```

### Check all Firewall rules directly with iptables

```
sudo iptables -L
```
