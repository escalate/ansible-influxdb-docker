# Ansible Role: influxdb-docker

An Ansible role that manages InfluxDB OSS Docker container on Raspberry Pi OS and Debian based systems.

## Requirements

The Docker daemon should be already installed and running on the host side.
I recommend using of the Ansible role [escalate.docker](https://github.com/escalate/ansible-docker) to manage the Docker daemon.

This role is tested with Ansible version greater equal 2.9.

## Install

```
$ ansible-galaxy install escalate.influxdb-docker
```

## Role Variables

Please see [defaults/main.yml](https://github.com/escalate/ansible-influxdb-docker/blob/master/defaults/main.yml) for a complete list of variables that can be overridden.

## Dependencies

None

## Example Playbook

```
- hosts: all
  roles:
    - escalate.influxdb-docker
```

## License

MIT
