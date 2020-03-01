# Anisible jenkins 

ansible jenkins example

## Installation

Please install ansible and ssh keys

```bash
#generate keys install keys in jenkins CI server so it can be use keys can be stored multiple ways ansible vault, vault(hashicorp)
ssh-keygen

ssh-copy-id username@server

```

## Usage

CI jenkins must be setup to put the ssh-keys 

```bash
ansible-playbook -i hosts site.yml

```