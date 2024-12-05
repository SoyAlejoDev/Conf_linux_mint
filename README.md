## Rpositorios Linux mint

```
#repoOfficial
#deb http://packages.linuxmint.com virginia main upstream import backport #id:linuxmint_main
#deb http://archive.ubuntu.com/ubuntu jammy main restricted universe multiverse
#deb http://archive.ubuntu.com/ubuntu jammy-updates main restricted universe multiverse
#deb http://archive.ubuntu.com/ubuntu jammy-backports main restricted universe multiverse
#deb http://security.ubuntu.com/ubuntu/ jammy-security main restricted universe multiverse
#repo oriente
#deb http://repos.uo.edu.cu/linuxmint/ virginia main upstream import backport #id:linuxmint_main
#repoUCI
deb http://ubuntu.uci.cu/ubuntu/ jammy main restricted universe multiverse
deb http://ubuntu.uci.cu/ubuntu/ jammy-backports main restricted universe multiverse
deb http://ubuntu.uci.cu/ubuntu/ jammy-updates main restricted universe multiverse
deb http://ubuntu.uci.cu/ubuntu/ jammy-security main restricted universe multiverse

```

### Enviroment

```
http_proxy="http://127.0.0.1:3128/"
https_proxy="http://127.0.0.1:3128/"
no_proxy="localhost,*uci.cu,.uclv.cu,127.0.0.1"
```
