run command
```
>docker build -t autossh:1.0.0 .
>docker run -d -v ~/.ssh/id_rsa:/id_rsa -p1080:1080 -e SSH_HOSTUSER=user -e SSH_HOSTNAME=host -e SSH_HOSTPORT=22 autossh:1.0.0  
```
