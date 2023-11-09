# ansible

automated development environment setup

## Instructions

Setup a new SSH Key and name it `private`, then register it at GitHub, [see instructions](https://docs.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent).

### Bootstrap Darwin

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/JacobSoderblom/ansible/HEAD/bin/darwin)"
```

### Bootstrap Debian

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/JacobSoderblom/ansible/HEAD/bin/debian)"
```
