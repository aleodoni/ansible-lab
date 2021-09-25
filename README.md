# Ansible Laboratory
Some study and tests about how to use ansible to automate repetitive jobs.

# Repository structure
```
> group_vars--+ (group variables directory)
> host_vars---| (host variables directory)
> playbooks---+ (playbooks directory )
. hosts.example   (inventory with all your hosts - YOU MUST RENAME IT TO hosts)
```
# Setup
You must do some initial setup before run the playbooks:

1. Rename hosts.example to hosts
2. Update hosts with all servers you want to test playbooks
3. Go to host_vars directory and rename the file your-host-name.yml with the first host name you added into hosts file
4. Do the same thing for all other hosts in your hosts file.

# Playbooks

## hello-world
This simple playbook shows group and host vars

## all-apt-update.yml
This is your first real playbook. It updates the package list for all servers in your
inventory (hosts).
