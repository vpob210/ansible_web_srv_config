.
├── ansible.cfg
├── inventory.ini
├── playbooks
│   └── configure-webserver.yml
├── roles
│   ├── configure-firewall
│   │   └── tasks
│   │       └── main.yml
│   ├── install-nginx
│   │   ├── tasks
│   │   │   ├── main.yml
│   │   │   └── nginx.service.j2
│   │   ├── templates
│   │   │   └── nginx
│   │   │       └── nginx_test.conf
│   │   └── vars
│   │       └── main.yml
│   └── prepare-disk
│       └── tasks
│           └── main.yml
└── vault
    └── sudo_password.yml
