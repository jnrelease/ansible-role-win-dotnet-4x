Ansible Role: win_dotnet_4x
=========

Installs [.NET Framework 4.x](https://dotnet.microsoft.com/en-us/download/dotnet-framework) on a Windows host.

Requirements
------------

None.

Role Variables
--------------

    dotnet_version: 4.8

Sets the .NET Framework version (default `4.8`)


Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: win_dotnet_4x

License
-------

BSD

Author Information
------------------

This role was create by Javel Wilson.
