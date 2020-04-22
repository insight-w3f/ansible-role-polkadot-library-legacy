polkadot-library
=========

This role prepares the node for installation of the Polkadot client as a full "library" node.
It incorporates the necessary tasks from the W3F _polkadot_common_ role, and as such, should not be used together.

Requirements
------------

This role does not currently have any requirements.

Role Variables
--------------



Dependencies
------------



Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: insight_infra.polkadot_library }

License
-------

Apache 2.0

Author Information
------------------

Maintained by [Richard Mah](https://github.com/shinyfoil) for [Insight Infrastructure](https://github.com/insight-infrastructure)
