# deploy_esphome_script

Ansible Playbook for the creation of a light controller with buttons and adressable LEDs

## Requirements
You need to install ansible
``` bash
pip install ansible
```

## Configuration
Copy example-config.yml to config-yml and add your configuration

## Execute Playbook
To create the config file you have to execute the playbook
``` bash
ansible-playbook -i inventory.ini create_panel_file.yml
```
You will find the created Config file in the output folder.
``` bash
esphome run panel.yml
```