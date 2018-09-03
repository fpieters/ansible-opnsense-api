# Ansible Role: OPNSense api

Used in [network](https://github.com/naturalis/network/) repo.

Runnable with:
```bash
ansible-playbook playbooks/opnsense_api.yml -i environments/prod --ask-vault-pass
```

## Requirements

config.xml file placed in files/

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```bash
api_port:
api_key:
api_secret:
api_url:
```

## Dependencies

None.

## Example Playbook

- hosts: firewall
  roles:
    - ansible-role-opnsense-api

## License

Apache2
