# Simple web infra deployed by Ansible with Docker, OpenLDAP and Traefik 

[![Author](https://img.shields.io/badge/author-@FelixLusseau-blue)](https://github.com/FelixLusseau)

<a href="https://www.ansible.com/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/2/24/Ansible_logo.svg" alt="ansible" width="40" height="40"/> </a>
<a href="https://www.docker.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="docker" width="40" height="40"/> </a> 
<a href="https://www.traefik.io/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/traefik/traefik/master/docs/content/assets/img/traefik.logo.png" alt="traefik" width="40" height="40"/> </a>
<a href="https://httpd.apache.org/" target="_blank" rel="noreferrer"> <img src="https://www.apache.org/logos/res/httpd/default.png" alt="apache" height="30"/> </a>
<a href="https://www.nginx.com" target="_blank" rel="noreferrer"> <img src="https://www.nginx.com/wp-content/uploads/2020/05/NGINX-product-icon.svg" alt="nginx" width="40" height="40"/> </a>
<a href="https://www.openldap.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/en/c/c7/OpenLDAP-logo.png" alt="openldap" height="40"/> </a>

## Usage

To run the project, you need to have [Docker](https://www.docker.com/) and [Ansible](https://www.ansible.com/) installed on your machine.

### 1. Clone this repo

### 2. Install the dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the playbook

```bash
ansible-playbook -i inventory playbook_tp1.yaml
```
