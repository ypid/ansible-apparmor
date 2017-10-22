## [![DebOps](https://debops.org/images/debops-small.png)](https://debops.org) apparmor

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](https://img.shields.io/travis/debops-contrib/ansible-apparmor.svg?style=flat)](https://travis-ci.org/debops-contrib/ansible-apparmor)
[![test-suite](https://img.shields.io/badge/test--suite-ansible--apparmor-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-apparmor/)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-debops--contrib.apparmor-660198.svg?style=flat)](https://galaxy.ansible.com/debops-contrib/apparmor)


AppArmor is able to restrict what programs can do and access based on policies for those programs.

See [AppArmor in the Debian Wiki](https://wiki.debian.org/AppArmor/HowToUse).

By default (e.g. no [auditd] installed) log messages from AppArmor are
logged via syslog to the kernel facility which usually ends up under
`/var/log/kern.log`.

[auditd]: https://packages.debian.org/search?keywords=auditd

### Installation

This role requires at least Ansible `v2.1.3`. To install it, run:

```Shell
ansible-galaxy install debops-contrib.apparmor
```

### Documentation

<!-- FIXME: Change to the canonical URL when it has been setup. https://github.com/debops/docs/issues/111 -->
More information about `debops-contrib.apparmor` can be found in the
[official debops-contrib.apparmor documentation](https://debops-contrib.readthedocs.io/en/latest/ansible/roles/ansible-apparmor/docs/).

## Contributing

Please note that this repository is not the upstream repository where changes should be contributed to.
Head over to https://github.com/debops/debops where you can find the contents of this repo and where changes are welcome.



### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://debops.org/) for a complete solution to run your Debian-based infrastructure.





### Authors and license

- [Robin Schneider](https://docs.debops.org/en/latest/debops-keyring/docs/entities.html#debops-keyring-entity-ypid) (maintainer) | [e-mail](mailto:ypid@riseup.net) | [GitHub](https://github.com/ypid)

License: [GPL-3.0](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of [DebOps Contrib](https://github.com/debops-contrib/debops-contrib). README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
<!-- Ansigenome sources: https://github.com/ypid/ypid-ansible-common/tree/master/template_READMEs/debops-contrib -->
