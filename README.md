# Ansible Role: Remi Mirror

Installs the Remi mirroring role

## Requirements

None.

## Role Variables

See `defaults/main.yml`.

## Dependencies

nexcess.mirror

## Add to Requirements

    - src: https://github.com/nexcess/ansible-role-remi-mirror.git
      name: nexcess.remi-mirror

## Example Playbook

    - hosts: servers
      roles:
        - nexcess.remi-mirror

## License

MIT / BSD
