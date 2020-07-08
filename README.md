# VPS Setup

VPS setup is a simple script to easily setup a Docker Swarm with the following resources:

- ufw firewall deixando 80, 443 e 2222 no SSH
- Treafik LB with Let's Encrypt: choose 
- Google Authenticator
- GitLab Runner

```
$ curl https://raw.githubusercontent.com/jairsjunior/vps-setup/master/install.sh | bash
```

