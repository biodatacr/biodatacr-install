# BIODATACR installation scripts

This repository is a fork from [https://github.com/AtlasOfLivingAustralia/ala-install](https://github.com/AtlasOfLivingAustralia/ala-install) on 2021-07-05.

## Clonning
```
$ git clone https://github.com/biodatacr/biodatacr-install.git
```

## Installation

Main portal

```
$ ansible-playbook --private-key ~/.ssh/living-atlas --user ubuntu --become -i ansible/inventories/living-atlas ansible/ala-demo.yml
```

Spatial portal

```
$ ansible-playbook --private-key ~/.ssh/living-atlas --user ubuntu --become -i ansible/inventories/living-atlas-spatial ansible/spatial.yml
```
