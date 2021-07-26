# workstation-vm
Customizations for the workstation VM

# customize-workstation
This playbook manages
- Git configuration
- Powerline for bash (https://github.com/powerline/powerline)
- pre-commit
- Github key (optional)

## Github key

Create a YAML file with `ghkey` key with the value of the SSH key for Github.

```
ansible-playbook -K customize-workstation.yml -e @ghkey.yml
```