# Ansible general

Configures base services, sets up users and keys for rails servers

# Usage

Set `user` variable. Its user who will run rails application.

Set `root_authorized_keys` with array of keys, that will be added to roots `authorized_keys` file

Set `user_authorized_keys` with array of keys, that will be added to users `authorized_keys` file