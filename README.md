# AWX Dynamic Playbook

> This repository provides a playbook template for AWX, allowing dynamic execution via API.

## 🔧Usage
* Use this repository as an SCM source in AWX.
* Execute playbooks dynamically by passing extra_vars via API.

## 📌 Notes
* The `value` parameter should be a valid YAML string defining tasks.
* `target_hosts` can be specified to control execution scope.
