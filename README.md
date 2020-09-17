# common role

Instals base packages.
Define a valid FQDN.
Set the timezone to `Etc/UTC`
Creates an empty `facts.d` directory for later use.
Extends the `/etc/hosts`



## dependencies

## test

requies `tox`and `molecule`

```
tox -e py37-ansible28 -- molecule test --scenario-name default
```
