# provision

## Setup
Setup your local development machine using ansible playbook. In a terminal, execute the following:

```
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

$ brew tap homebrew/cask

$ brew install python

$ python3 -m pip install --user ansible
```

To run, you may be required to start a new terminal window.


## Provisioning

The following can be run as you or others add to your playbook. It is intended to be able to run multiple times even when some of the applications are already installed.

```
$ ansible-playbook playbook.yml
```