# ansible-middleware-ee

Execution Environment providing middleware automation collections


## Installation

Install with ansible-navigator:

```
# ansible-navigator --eei quay.io/ansible-middleware/ansible-middleware-ee:latest
```

Sample config for ansible-navigator taken from our tests:

```

---
ansible-navigator:
  ansible:
    config:
      path: ./ansible.cfg
    playbook:
      path: test.yml
  execution-environment:
    container-engine: podman
    enabled: true
    image: quay.io/ansible-middleware/ansible-middleware-ee:latest
  logging:
    level: info
  playbook-artifact:
    enable: false
```


## Usage

Short tutorial showing the whole procedure to deploy keycloak on a kvm/qemu virtual machine using ansible-navigator and ansible-middleware-ee:

[![asciicast](https://asciinema.org/a/477628.png)](https://asciinema.org/a/477628?autoplay=1)
