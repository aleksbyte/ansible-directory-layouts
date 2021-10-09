```
Explain Ansible directories

- tasks:    The main list of tasks to be exectued by role. it contains the main.yml file.
- files:    Contains files that can be deployed by this role
- handlers: Contains handlers which may be used by this role or even anywhere outside this role.
- defaults: Contains the default variables used by this role.
- meta:     Defines metadata for this role. it contains file role dependencies.
- vars:     This directory consists of other variables that used by the roles.
               These variables can be defined in ansible playbook.

```
.
├── README.md
├── basic
│   ├── .ansible-lint
│   ├── .gitignore
│   ├── .yamllint
│   ├── README.md
│   ├── ansible.cfg
│   ├── files
│   ├── inventory.yml
│   ├── requirements.yml
│   ├── site.yml
│   ├── tasks
│   └── vars
└── basic-plus
    ├── .ansible-lint
    ├── .gitignore
    ├── .yamllint
    ├── README.md
    ├── ansible.cfg
    ├── defaults
    ├── files
    ├── handlers
    ├── inventory.yml
    ├── mmeta
    ├── requirements.yml
    ├── site.yml
    ├── tasks
    ├── templates
    ├── tests
    └── vars
```
```
13 directories, 16 files

Git clone any sub-directories ( use ghclone https://github.com/HR/github-clone). Example:
  ghclone https://github.com/aleksbyte/ansible-directory-layouts/tree/main/basic-plus
  ghclone https://github.com/aleksbyte/ansible-directory-layouts/tree/main/basic && mv basic myplaytest

```
9 directories, 26 files
