# Ansible Lab

Modular scenario-driven structure:
- Edit/add dynamic variables in `inventory/`.
- All automation logic/playbooks are in `playbooks/` and are static.
- Use `main.yml` as your orchestrator; change var file or playbooks for new scenarios.

Run with: `ansible-playbook main.yml`
