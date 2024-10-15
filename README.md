[![CI](https://github.com/ngine-io/ansible-role-syncthing/actions/workflows/ci.yml/badge.svg)](https://github.com/ngine-io/ansible-role-syncthing/actions/workflows/ci.yml)

# Ansible Role: syncthing

Installs [syncthing](https://syncthing.net) on Debian Linux.

## Requirements

See `requirements.txt`.

## Installation

Via `requirements.yml`:

```yaml
---
# file: requirements.yml
roles:
  - name: ngine_io.syncthing
    version: v0.1.0
```

To install:

```
ansible-galaxy install -r requirements.yml
```
## License

MIT / Apache2

## Author Information

This role was created in 2024 by [René Moser](https://renemoser.net).
