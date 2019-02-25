# You must sure in ROOT

```wget --no-check-certificate -O shadowsocks.sh https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks.sh```

# If you don't have this command, install WGET

```yum -y install wget```

# If you download successful, change the file permission

```chmod +x shadowsocks.sh```

# Set your shadowsocket or anything else

```./shadowsocks.sh 2>&1 | tee shadowsocks.log```

# Waiting for few minutes...

# Ckeck your process

```ps -ef|grep shadowsocks```
