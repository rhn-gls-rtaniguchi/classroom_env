## About

This Ansible Playbook is suitable to be used in Red Hat Training classes and is tested on RHEL 8 and RHEL 9 environments. 

## Contributing

Create a branch -> Create a merge request -> Assign me as a reviewer.

## Getting started

Requires Ansible to be installed.

```
git clone https://gitlab.com/rgdacosta/classroom_env.git

cd classroom_env

ansible-playbook playbook.yml
```

## Using

Check out these files for more information:

~/.bashrc

~/.vimrc

~/.tmux.conf

Resolution and gnome terminal profiles are set.

## OpenShift classes

The RHT_OCP4_ variables can be difficult to type at times, often resulting in typos and hindered success. 

Newer, simpler variables are available should `/usr/local/etc/ocp4.config` exist.

```
M=$RHT_OCP4_MASTER_API
WC=$RHT_OCP4_WILDCARD_DOMAIN
NS=$RHT_OCP4_NEXUS_SERVER
U=$RHT_OCP4_DEV_USER
P=$RHT_OCP4_DEV_PASSWORD
G=$RHT_OCP4_GITHUB_USER
Q=$RHT_OCP4_QUAY_USER
```

This means that you are able to use `$NS` when referring to the Nexus Server

Logging into clusters:

```
lcl - local cluster login as admin
mcl - managed cluster login as admin (DO480)
dl - developer login
```



