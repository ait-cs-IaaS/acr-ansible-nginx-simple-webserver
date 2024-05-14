# Ansible-Role: acr-ansible-nginx-simple-webserver

AIT-CyberRange: Installs and run simple nginx server


## Requirements

- Debian or Ubuntu 

## Role Variables

```yaml
nginx_conf_src: nginx.conf.j2
nginx_conf_dest: default.conf
```

## Example Playbook

```yaml
- hosts: all
  roles:
    - acr-ansible-nginx-simple-webserver
      vars:
        nginx_conf_src: nginx.conf.j2
        nginx_conf_dest: default.conf
```

## License

GPL-3.0

## Author

- Lenhard Reuter