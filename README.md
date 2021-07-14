Install packages
=========

Install system packages for Ubuntu and Debian systems family.


Role Variables
--------------

add_packages_list - list of package names to isntall
remove_packages_list - list of package names to remove from system
sources_keys - list of apt keys to add (for custom apt repositories)
sources_repos - list of source repos entries (for custom apt repositories)

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
