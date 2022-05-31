# unifi-controller

## Raspberry Pi Setup

- [Raspberry Pi Imager](https://www.raspberrypi.com/software/)
- [Rasbperry Pi OS](https://www.raspberrypi.com/software/operating-systems/)

Copy SSH key to the raspberry pi
```sh
ssh-copy-id -i ~/.ssh/mykey user@host
```

## Install Docker and Docker-Compose On Raspberry Pi and start Unifi Controller

```
ansible-playbook -i inventory main.yml
```

## Links
- [How ssh-copy-id works](https://www.ssh.com/academy/ssh/copy-id)
