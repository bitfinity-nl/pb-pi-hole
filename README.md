# pb-pi-hole
Ansible Playbook for installing a PI-Hole server


## ~/.ansible-config.yml ##

1. Create an ansible config file:
```
---
# Title: PI-Hole server
#
# Author: Bitfinity / L. Rutten
# Owner: Bitfinity / L. Rutten
#
# File: ~/.ansible-config.yml
#
# Description:
#   Playbook for installing a PI-Hole server.
#

# -- PI-Hole settings --
pihole_region : 'Europe/Amsterdam'

```

2. Set permission on configuration file: `chmod 600 ~/.ansible-config.yml`
3. Install dependencies: `apt install -y ansible git`
