# Mauro’s dotfiles

## Installation

### Ansible

Dependencies are managed with [uv](https://docs.astral.sh/uv/). Install uv, then run:

```
uv sync
uv run ansible-galaxy install -r requirements.yml
uv run ansible-playbook -i inventory.yml ./setup-system.yml
```
