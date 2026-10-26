# Ansible

> Ansible is a configuration management and automation tool that helps transform a plain server into an     application-ready server by installing the required software, configuring services, and deploying applications.

**Using Ansible, you can automatically:**
- Install required packages.
- Install Java, Python, or Nginx.
- Create users and directories.
- Configure services.
- Copy application files.
- Start and enable services.
- Configure required settings.

**Push V/S Pull**

**Push:** The control node sends configurations to target servers. \n

**Pull:** Target servers retrieve configurations from a central location.

**Important:** Ansible normally uses the Push model. Ansible also supports the Pull model through ansible-pull.



**Ansible Pull & Push**

![Ansible Pull & Push](ansible-push-vs-pull.png)
---------------