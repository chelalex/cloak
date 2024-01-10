cloak
=========

Install and configure Cloak ansible role<br>
Available for Ubuntu 22.04 LTS<br>

    cloak
    ├── README.md
    ├── files
    │   ├── ckclient.json
    │   └── ckserver.json
    ├── tasks
    │   └── main.yml
    └── vars
        └── main.yml

More: https://github.com/cbeuw/Cloak

Requirements
------------

openssl

Role Variables
--------------

**cloak:**<br>
&nbsp; **version:** *chosen cloak version*<br>

Example Playbook
----------------

    - hosts: server,client
      roles:
         - cloak
