[![Build Status](https://travis-ci.org/opspluslove/ansible-opsdash-agent.svg?branch=master)](https://travis-ci.org/opspluslove/ansible-opsdash-agent)

opsdash-agent
=========

Ansible role to install and config the [OpsDash](http://opsdash.com/) agent

Role Variables
--------------

```yml
# Defaults
opsdash_agent_server: "localhost"
opsdash_agent_name: "{{ ansible_hostname }} agent"
opsdash_agent_metrics_port: 6273
opsdash_agent_data_port: 6273
opsdash_agent_access_logs:
  - name: nginx
    path: /var/log/nginx/access.log
  - name: apache
    path: "/var/log/httpd/access_log, /var/log/apache2/*access.log"
```

Example Playbook
----------------

_TODO_
