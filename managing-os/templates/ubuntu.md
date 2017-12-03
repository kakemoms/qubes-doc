---
layout: doc
title: Ubuntu Template
permalink: /doc/templates/ubuntu/
redirect_from:
- /doc/ubuntu/
- /en/doc/templates/ubuntu/
- /doc/Templates/Ubuntu/
- /wiki/Templates/Ubuntu/
---

Ubuntu template(s)
==================

If you would like to use Ubuntu Linux distribution in your AppVMs, you can build and
install one of the available Ubuntu templates. These templates are currently not
available in ready to use binary packages, because Canonical does not allow
redistribution of a modified Ubuntu. The redistribution is not allowed by their
[Intellectual property rights policy](https://www.ubuntu.com/legal/terms-and-policies/intellectual-property-policy).


Install
-------

It can built using [Qubes Builder](/doc/qubes-builder/). You can also access its
documentation in the [source code
repository](https://github.com/QubesOS/qubes-builder/blob/master/README.md).

To quickly prepare the builder configuration, you can use the `setup` script
available in the repository - it will interactively ask you which templates you
want to build.

The build for Ubuntu 14.4 LTS (Trusty) should be straightforward.

The build for Ubuntu 16.4 LTS (Xenial) is straightforward.


Install guide for dummies
-------------------------
A step-by-step guide that seems to get around most problems (if above instructions fails):
https://www.reddit.com/r/Qubes/comments/5vzg04/idiots_guide_to_installing_qbuntu_ubuntu_1604/


If you want to help in improving the template, feel free to
[contribute](/doc/contributing/).
