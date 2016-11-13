## [![DebOps](https://debops.org/images/debops-small.png)](https://debops.org) bootstrap

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](https://img.shields.io/travis/debops/ansible-bootstrap.svg?style=flat)](https://travis-ci.org/debops/ansible-bootstrap)
[![test-suite](https://img.shields.io/badge/test--suite-ansible--bootstrap-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-bootstrap/)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-debops.bootstrap-660198.svg?style=flat)](https://galaxy.ansible.com/debops/bootstrap)


`debops.bootstrap` is an Ansible role that helps prepare a given
Debian/Ubuntu host to be managed by Ansible. It will install required
Python packages, configure hostname and domain, create an admin account and
set up SSH public keys for passwordless SSH access.

### Installation

This role requires at least Ansible `v2.0.0`. To install it, run:

```Shell
ansible-galaxy install debops.bootstrap
```

### Documentation

More information about `debops.bootstrap` can be found in the
[official debops.bootstrap documentation](https://docs.debops.org/en/latest/ansible/roles/ansible-bootstrap/docs/).



### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://debops.org/) for a complete solution to run your Debian-based infrastructure.





### Authors and license

- [Maciej Delmanowski](https://docs.debops.org/en/latest/debops-keyring/docs/entities.html#debops-keyring-entity-drybjed) (maintainer) | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)
- [Robin Schneider](https://docs.debops.org/en/latest/debops-keyring/docs/entities.html#debops-keyring-entity-ypid) | [e-mail](mailto:ypid@riseup.net) | [GitHub](https://github.com/ypid)

License: [GPL-3.0](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of [DebOps](https://debops.org/). README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
