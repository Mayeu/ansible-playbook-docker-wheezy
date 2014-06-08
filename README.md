#Docker

Really simple role that install docker on Debian 7. Waiting for Debian 8.

No dependencies. The only requirement is using Debian 7.

##Example Playbook

Install the role: `ansible-galaxy install Mayeu.docker-wheezy`

```yaml
- hosts: servers
  roles:
    - Mayeu.docker-wheezy
```

##License

BSD
