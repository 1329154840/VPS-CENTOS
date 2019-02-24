# You must sure in ROOT

```wget --no-check-certificate -O shadowsocks-all.sh https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks-all.sh```

# If you don't have this command, install WGET

```yum -y install wget```

# If you download successful, change the file permission

```chmod +x shadowsocks-all.sh```

# Set your shadowsocket or anything else

```./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log```

# Waiting for few minutes...

# Ckeck your process

```ps -ef|grep shadowsocks```
