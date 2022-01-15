# Configuring a Linux Minecraft Server
## Overview
These playbooks are designed to create a single minecraft instance on a redhat based system.

configure_server.yml
This playbook installs dependencies and configures a system user to run the minecraft instance.

world_build.yml
This playbook builds the world instance and starts it.

## Customize 
Memory allocation can be tweaked to fit your hardware by adjusting the "-Xmx" line in minecraft@.service