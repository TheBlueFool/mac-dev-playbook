<img src="https://raw.githubusercontent.com/TheBlueFool/mac-dev-playbook/master/files/Mac-Dev-Playbook-Logo.png" width="250" height="156" alt="Mac Dev Playbook Logo" />

# Disclaimer
This repo has been forked from (geerlingguy)[https://github.com/geerlingguy/mac-dev-playbook]
His playbook is better than mine, go to his.

# Bootstrap New Development Mac Ansible Playbook

Welcome back Richard!

## Installation

  1. `xcode-select --install`
  2. `export PATH="$HOME/Library/Python/3.8/bin:/opt/homebrew/bin:$PATH"`
  3.  `sudo pip3 install --upgrade pip`
  4.  `pip3 install ansible`
  5. Clone or download this repository to your local drive.
  6. `ansible-galaxy install -r requirements.yml` 
  7. `ansible-playbook main.yml --ask-become-pass`

Any variable can be overridden in `config.yml`; see the supporting roles' documentation for a complete list of available variables.

### Things that still need to be done manually


  1. Set CAPS LOCK to ESC
  2. Setup Alfred
  4. Setup Bartender
  5. Setup Firefox
  6. Set up Jetbrains
  7. 




## Author
Local modifications by Richard Pavis

This project was created by [Jeff Geerling](https://www.jeffgeerling.com/) (originally inspired by [MWGriffin/ansible-playbooks](https://github.com/MWGriffin/ansible-playbooks)).


