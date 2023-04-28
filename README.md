# ansible-modules-core

## Description

New option 'uniq' added to module 'lineinfile'.

With uniq:yes non-uniq lines of 'line' content are deleted.

```
  lineinfile:
    path: ....
    line: ...
    uniq: yes
```

## Install

```
cd $HOME/.ansible
git clone git@github.com:mcgru/ansible-modules-core.git
```
### Per-project changes in ansible.cfg:

```
[defaults]
...
library = $HOME/.ansible/ansible-modules-core:$HOME/.ansible/plugins/modules
```
