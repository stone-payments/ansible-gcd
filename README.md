# stone-payments.gcd

Ansible role to install and configure [gcd](https://github.com/stone-payments/gcd).

## Usage

### Quickstart
```yaml
- name: install gcd
  hosts: all
  roles: stone-payments.gcd
```

### Custom setup
```yaml
- name: install gcd
  hosts: all
  roles: stone-payments.gcd
  vars:
    docker_host: "/var/run/docker.sock"
    sweep_interval: "120"
    remove_healthy_containers_exited: false
```

## Contributing
Just open a PR.

## License
This role is distributed under the MIT license.