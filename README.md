# Ansible Automation Platform 2.6 – Resource Automation

## Overview

This repository contains Ansible playbooks and supporting files used to **create, manage, and maintain resources in Ansible Automation Platform (AAP) 2.6**.

The automation is built using the following Red Hat–supported collections:

- `ansible.controller`
- `infra.aap_configuration`

These playbooks are designed to be **idempotent**, **version-controlled**, and **repeatable**, following Infrastructure as Code (IaC) best practices for AAP environments.

---

## Goals of This Repository

- Automate configuration of Ansible Automation Platform 2.6
- Standardize AAP resource creation across environments
- Reduce manual configuration through the UI
- Enable repeatable, auditable, and scalable automation
- Support GitOps-style workflows

---

## What This Repository Automates

Using `ansible.controller` and `infra.aap_configuration`, this repository can manage:

- Organizations
- Teams
- Users
- Credentials
- Credential Types
- Projects
- Inventories
- Inventory Sources
- Execution Environments
- Instance Groups
- Job Templates
- Workflow Job Templates
- Notifications
- RBAC assignments

---

## Collections Used

This repository relies on the following Ansible collections:

```yaml
collections:
  - ansible.controller
  - infra.aap_configuration

