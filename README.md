Common packages
========

Installation
--------------

`ansible-galaxy install palkan.common_setup`

Role Variables
--------------

`defaults/main.yml`

Contains the only one variable `common_setup.packages` which contain the following list of packages to be installed:

- build-essential
- automake
- bison
- autoconf
- pkg-config
- libreadline6
- libreadline6-dev
- openssl
- libssl-dev
- libncurses5-dev
- curl
- git
- zlib1g
- zlib1g-dev
- libyaml-dev
- libsqlite3-dev
- libxml2-dev
- libxslt1-dev
- nfs-common
- ntp
- vim
- htop

Example Playbook
-------------------------
    - hosts: servers
      roles:
         - palkan.common_setup
