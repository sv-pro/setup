1. remove existing `/etc/resolv.conf` link: `sudo unlink /etc/resolv.conf`
2. create new empty file: `sudo touch /etc/resolv.conf`
3. enter a nameserver: `nameserver 8.8.8.8`
4. run `sudo apt update && sudo apt -y upgrade`
5. 
