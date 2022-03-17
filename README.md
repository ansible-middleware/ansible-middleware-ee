# ansible-middleware-ee

Execution Environment providing middleware automation collections


## Installation

Login into container registry and install with ansible-navigator:

```
# podman login quay.io -u='<quay.io_user'
Password: <quay.io_token>

# ansible-navigator --eei quay.io/ansible-middleware/ansible-middleware-ee:latest
```

## Usage

Short tutorial showing the whole procedure to deploy keycloak on a kvm/qemu virtual machine using ansible-navigator and ansible-middleware-ee:

[![asciicast](https://asciinema.org/a/477628.png)](https://asciinema.org/a/477628?autoplay=1)
