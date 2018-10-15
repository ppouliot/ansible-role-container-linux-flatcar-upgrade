# Ansible Role: container-linux-flatcar-upgrade

Flatcar Linux is an immutable Linux distribution for containers. It is a friendly fork of CoreOS’s Container Linux and as such, compatible with it.
This role will upgrade a running CoreOS Instance to [FlatCar Linux](https://flatcar-linux.org).

## Requirements

A Container Linux instance that has already been bootstrapped and is functionally managed by Ansible.   Bootstrapping can be achived by using a the [ppouliot/container-linux-bootstrap](https://github.com/ppouliot/ansible-role-container-linux-bootstrap).


## Role Variables

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

## Dependencies

* ppouliot/container-linux-azure (optional)
* ppouliot/container-linux-bootstrap


## Example Playbook
------------------

Here is an example of typical usage.


```
- hosts: localhost
  gather_facts: True
  roles:
    - container-linux-azure
```

## Contributors
------------

 * Peter Pouliot <peter@pouliot.net>

## Copyright and License
---------------------

Copyright (C) 2018 Peter J. Pouliot

Peter Pouliot can be contacted at: peter@pouliot.net

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

