# Ansible Configuration
I made this repo to automate setting up a WSL instance.

**ALWAYS** review arbitrary code before running it on your system.

## Run
`ansible-playbook setup.yml --ask-vault-pass`

## Tasks
- Configure ssh certs
- Configure dotfiles
- Install node v18 and npm
- Install python toolchain

## Dependencies
- software-properties-common
- ansible
- build-essential
