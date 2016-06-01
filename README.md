fluentd-packages
================

[![Build Status](https://travis-ci.org/lsst-sqre/ansible-fluentd-packages.svg?branch=master)](https://travis-ci.org/lsst-sqre/ansible-fluentd-packages)

Install [Fluentd](http://www.fluentd.org/) packages using [Ansible](http://docs.ansible.com/) for LSST SQuaRE infrastructure.

Example Playbook
----------------

    - hosts: server
      roles:
         - { role: lsst-sqre.fluentd-packages }

Versions
--------

Fluentd (td-agent v2 variant) using the [Treasure Data, Inc. repository](http://docs.fluentd.org/v0.12/categories/installation).

Tested using Ansible 2.1 which is currently in development.

License
-------

The MIT License. See the [LICENSE file](https://github.com/lsst-sqre/ansible-fluentd-packages/blob/master/LICENSE).
