# SSH Tunneling via AWS EC2

## Private Browsing

![](new-ip.png)

# Use a SSH Tunnel

![](SOCKS_v5.png)

# Change UA

![](ua.png)

# Setup the Tunnel

```
cd ~/.ssh
ssh -N -D 9090 ubuntu@3.133.101.213 -i kali-key.pem
```