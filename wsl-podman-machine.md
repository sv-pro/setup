Install missing software
```
sudo dnf install git iproute iputils bind-utils wget nano vim e2fsprogs
```

Install JDK
```
sudo dnf install java-17-openjdk-headless
```

Make configuration files inmodifiable

```
sudo chattr +i /etc/resolv.conf
sudo chattr +i /etc/wsl.conf
```
