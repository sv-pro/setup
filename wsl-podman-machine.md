Install missing software
```
sudo dnf install git iproute iputils bind-utils wget nano vim e2fsprogs
```

Install JDK
```
wget https://github.com/adoptium/temurin17-binaries/releases/download/jdk-17.0.5%2B8/OpenJDK17U-jdk_x64_linux_hotspot_17.0.5_8.tar.gz
sudo tar -zxf OpenJDK17U-jdk_x64_linux_hotspot_17.0.5_8.tar.gz -C /opt
# setup PATH env var
```
or
```
cat <<EOF > /etc/yum.repos.d/adoptium.repo
[Adoptium]
name=Adoptium
baseurl=https://packages.adoptium.net/artifactory/rpm/centos/8/$(uname -m)
enabled=1
gpgcheck=1
gpgkey=https://packages.adoptium.net/artifactory/api/gpg/key/public
EOF

yum update # update if you haven't already
yum install temurin-17-jdk
```

Make configuration files inmodifiable

```
sudo chattr +i /etc/resolv.conf
sudo chattr +i /etc/wsl.conf
```
