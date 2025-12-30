## Ansible Quickstarter - Samples

In this folder are small collection of practical **Ansible playbooks** for everyday operations.

It exists for one reason:

> “I know what I want to do, but I don’t remember the Ansible syntax.”

Each file answers one common question and can be used as a starting point or a copy-paste reference.


Use `ansible-playbook sample.yml --check --diff` when available to preview changes.

#### Repository structure

```bash
├── README.md
├── checks
│   ├── assert_file_exists.yaml
│   ├── assert_port_open.yaml
│   └── dry_run_example.yaml
├── files
│   ├── add-line.yaml
│   ├── ensure_block.yaml
│   └── replace_value.yaml
├── search
│   ├── find_files.yaml
│   └── grep_file.yaml
├── system
│   ├── create_user.yaml
│   ├── install_package.yaml
│   ├── manage_cron.yaml
│   ├── manage_service.yaml
│   ├── manage_sudoers.yaml
│   ├── set_hostname.yaml
│   └── set_timezone.yaml
└── validation
    └── nginx_validate_template.yaml
```