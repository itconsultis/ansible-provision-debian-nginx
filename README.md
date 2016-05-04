# provision-debian-nginx

Ansible role that installs the latest nginx web server from an nginx PPA

## Role Defaults
```
ppa_nginx     ppa:nginx/development
```

## Example Playbook

    - hosts: debian
      roles:
        - { role: provision-debian-nginx }

## License

MIT
