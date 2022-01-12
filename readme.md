# Ansible L2VPN Deployment playbook

This repo contains a playbooks that I've used to deploy L2VPN services between PE nodes in the GNS3 topology below.

!["GNS3 MPLS L3VPN topology"](images/topology.png)

## Variables structure



## Playbook structure

`provision_l2vpn_services.yaml` contains tasks to either generate local config files without pushing to the devices, pushing the generated configs to the devices, as well as doing both tasks together.