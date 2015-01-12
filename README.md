# ansible-trial
This is my first ansible playbooks.

## Description

This is my first ansible playbooks. You can create environment below.

- CentOs 7.0's basic environment.
- Nginx basic settings.
- Ruby 2.1.5 with rbenv.

I'm not good at creatig server-side environment. Any suggestions are my pleasure.

```
.
├── LICENSE
├── README.md
├── hosts
├── roles
│   ├── common
│   │   ├── defaults
│   │   │   └── main.yml
│   │   ├── files
│   │   ├── handlers
│   │   │   └── main.yml
│   │   ├── meta
│   │   │   └── main.yml
│   │   ├── tasks
│   │   │   └── main.yml
│   │   ├── templates
│   │   │   └── my_iptables.j2
│   │   └── vars
│   │       └── main.yml
│   ├── nginx
│   │   ├── defaults
│   │   │   └── main.yml
│   │   ├── files
│   │   ├── handlers
│   │   │   └── main.yml
│   │   ├── meta
│   │   │   └── main.yml
│   │   ├── tasks
│   │   │   └── main.yml
│   │   ├── templates
│   │   │   └── my_nginx.conf.j2
│   │   └── vars
│   │       └── main.yml
│   └── ruby
│       ├── defaults
│       │   └── main.yml
│       ├── files
│       ├── handlers
│       │   └── main.yml
│       ├── meta
│       │   └── main.yml
│       ├── tasks
│       │   └── main.yml
│       ├── templates
│       └── vars
│           └── main.yml
└── site.yml
```

## Environment

- CentOS 7.0 (Digital Ocean)
- Ansible 1.8.2

## References

- What's Ansible?: [Ansible is Simple IT Automation](http://www.ansible.com/home)
- Ansible Documents: [Ansible Documentation — Ansible Documentation](http://docs.ansible.com)

## Author

Naoki Morita /[page](http://moritanaoki.org) /[twitter](http://twitter.com/morizotter/)
