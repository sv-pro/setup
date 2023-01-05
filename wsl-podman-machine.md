Install missing software
```
sudo dnf install git iproute iputils bind-utils wget nano vim
```
Make configuration files inmodifiable

```
sudo chattr +i /etc/resolv.conf
sudo chattr +i /etc/wsl.conf
```
