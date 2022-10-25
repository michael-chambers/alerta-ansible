# Alerta Ansible Playbook
This repo contains an Ansible playbook to install Alerta on a server. It closely follows the tutorial for installing Alerta found in the [Alerta documentation](https://docs.alerta.io/gettingstarted/tutorial-1-deploy-alerta.html#tutorial-1). I'll add some common possible configurations as well.

Please note that the following files contain default values that will need to be changed in order for this playbook to actually work:
- _files/alerta-tls_ - server name and location of cert/key files
- _files/alertad.conf_ - `SECRET_KEY`