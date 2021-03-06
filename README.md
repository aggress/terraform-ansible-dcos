# terraform-ansible-dcos

## Overview

This ansible playbook installs DC/OS and is supposed to run on CentOS 7. The installation steps are based on the [Advanced Installation Guide][mesosphere-install] of DC/OS.

## Getting Started

All development is done on the master branch. Tested versions are identified via git tags. To get started, you can clone or fork this repo:

```
git clone https://github.com/jrx/terraform-ansible-dcos
```

Use `git tag` to list all versions:

```
git tag
v0.3.0-alpha
v0.4.0-alpha
```

Check out the latest version with:

```
git checkout v0.4.0-alpha
```

Here are some guides to follow to install the DC/OS cluster:

* [Install DC/OS On-Premises](docs/INSTALL_ONPREM.md)
* [Install DC/OS on AWS with Terraform](docs/INSTALL_AWS.md)

The guides to operate the cluster are located here:

* [Upgrade DC/OS](docs/UPGRADE.md)

## Documentation

All documentation for this project is located in the [docs](docs/) directory at the root of this repository.

## License
[DC/OS][github-dcos], along with this project, are both open source software released under the
[Apache Software License, Version 2.0](LICENSE).

## Acknowledgements
  * Current maintainer(s): [Jan Repnak][github-jrx]

[mesosphere-install]: https://docs.mesosphere.com/latest/installing/custom/advanced/
[github-dcos]: https://github.com/dcos/dcos
[github-jrx]: https://github.com/jrx
