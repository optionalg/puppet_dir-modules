puppet_dir-modules
==================

Konwn Issues
------------

* dns: always triggers a refresh TODO: create issue

TODO:
-----

* Fix or remove openvpn_wrapper
* Consider using puppetlabs/apt for providing backports (no stable support for wheezy on 1.2):
  * See https://github.com/puppetlabs/puppetlabs-apt/blob/master/manifests/backports.pp
  * See https://github.com/puppetlabs/puppetlabs-apt/blob/c0872c04a9db1f79a719fb5c963113746e6abf4e/manifests/params.pp
* Consider the need of update_augeas for squeeze, since it overlaps with augeas


