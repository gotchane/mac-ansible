# mac-ansible

## Requirements

* Xcode

https://developer.apple.com/xcode/

* Pip

```
$ sudo easy_install pip
```

* Ansible

```
$ sudo pip install ansible
```

* Homebrew

```
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

## Installation

Execlute a command below.
```
$ ansible-playbook -i inventories/hosts playbooks/macosx.yml
```
