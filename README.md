monit
=========
![monit](http://www.gogolek.co.uk/wp-content/uploads/2016/07/monit.png)

Install Ansible Role for Monit

# Build Status
![Build Status](https://travis-ci.org/iDustbin/monit.svg?branch=master "https://travis-ci.org/iDustbin/monit/") | [monit](https://travis-ci.org/iDustbin/monit/)

# Example playbook
    - hosts: all
      roles:
        - monit
      vars:
		monit_http_listen: "localhost"
		monit_http_port: "2812"
		monit_admin_user: "admin"
		monit_admin_pass: "password"
		monit_check_interval: 120

# Tested on
- Debian - 6 - **Squeeze**
- Debian - 7 - **Wheezy**
- Debian - 8 - **Jessie** 
- Debian - 9 - **Stretch** 
- RHEL - 7.6 - **Maipo**
- CentOS - **7.2**
- CentOS - **7.6**

# Todo´s
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
