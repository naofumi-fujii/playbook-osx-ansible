# playbook-osx
Setup my mac via Ansible.

# requires
- :warning: requires OS password for brew cask packages.
- https://brew.sh/index_ja
  - install homebrew
- `$ brew install ansible`
  - install ansible
- restart manually
  - for GoogleIME

# Quick Start
- git clone
- cd path/to/playbook-osx
- `$ ansible-playbook localhost.yml --ask-become-pass`

# dotfiles
naofumi-fujii/dotfiles https://github.com/naofumi-fujii/dotfiles
