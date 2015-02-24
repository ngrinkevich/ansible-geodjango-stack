ansible-geodjango-stack
====================

Ansible Playbook to deploy a minimal [GeoDjango](https://docs.djangoproject.com/en/1.7/ref/contrib/gis/install/) installation with a spatial database:
- Python
- Virtualenv
- Django
- Apache2 (Virtual hosts: app, static, media)
- PostgreSQL
- PostGIS

## Requirements
- [Ansible](http://docs.ansible.com/intro_installation.html)
- [Vagrant](http://www.vagrantup.com/downloads.html)
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)


## Quick Demo

This will deploy a simple djagno app [social-network-starter-kit](https://github.com/ngrinkevich/social-network-starter-kit). Go to the project root and run:

```
vagrant up
```

Add this to your **host** file

```
192.168.99.99 example.dev static.example.dev media.example.dev
```

Access the app: [http://example.dev](example.dev)



## Provision an existing server

comming soon ...

