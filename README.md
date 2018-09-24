# Demo: GitLab CI/CD - Ansible Lint
This project provides an environment to demonstrate a basic GitLab CI/CD pipeline for Ansible playbook linting.

GitLab URL: [https://172.16.2.50/](https://172.16.2.50/)

### Requirements
* Vagrant (tested on v2.1.5)
  * Vagrant [hostmanager](https://github.com/devopsgroup-io/vagrant-hostmanager) plugin (tested on v1.8.9)
* VirtualBox (tested on v5.2.18)
* Ansible (tested on v2.6.4)

### Provisioning Steps
* Clone this repo.
* Change to project dir:

```
$ cd demo-gitlab-cicd-ansible-lint
```

* Install required roles:

```
$ ansible-galaxy install -r roles/requirements.yml -p roles/
```

* Launch environment:

```
$ vagrant up
```
