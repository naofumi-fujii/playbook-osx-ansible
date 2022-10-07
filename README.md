# playbook-osx
Setup my mac via Ansible.

# requires
- :warning: requires OS password for brew cask packages.
- `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
- `brew install ansible`
- restart manually
  - for GoogleIME

# Quick Start
- git clone
- cd path/to/playbook-osx
- `$ ansible-playbook localhost.yml --ask-become-pass`

# dotfiles
naofumi-fujii/dotfiles https://github.com/naofumi-fujii/dotfiles
