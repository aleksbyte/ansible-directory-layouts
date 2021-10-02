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

```
.
├── README.md
├── basic
│   ├── README.md
│   ├── ansible.cfg
│   ├── files
│   ├── inventory.yml
│   ├── site.yml
│   ├── tasks
│   └── vars
└── basic-plus
    ├── README.md
    ├── ansible.cfg
    ├── defaults
    │   └── main.yml
    ├── files
    ├── handlers
    │   └── main.yml
    ├── inventory.yml
    ├── meta
    │   └── main.yml
    ├── site.yml
    ├── tasks
    │   └── main.yml
    ├── templates
    ├── tests
    │   ├── inventory
    │   └── test.yml
    └── vars
        └── main.yml
```
13 directories, 16 files
