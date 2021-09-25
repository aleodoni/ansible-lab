# Ansible Laboratory
Some study and tests about how to use ansible to automate repetitive jobs.

# Repository structure
```
> group_vars--+ (group variables directory)
> host_vars---| (host variables directory)
> playbooks---+ (playbooks directory )
. hosts.example   (inventory with all your hosts - YOU MUST RENAME IT TO hosts)
```

# Playbooks

## hello-world
This simple playbook shows group and host vars

## all-apt-update.yml
This is your first real playbook. It updates the package list for all servers in your
inventory (hosts).
