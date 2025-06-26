# Ansible RHEL Web Server on AWS

## Overview
Automates Apache (`httpd`) deployment on an RHEL EC2 instance using Ansible.

## Setup
1. Clone: `git clone https://github.com/rohinkumili/working-with-ansible.git`
2. Update `inventory/hosts.ini` with EC2 IP.
3. Run: `ansible-playbook -i inventory/hosts.ini playbooks/httpd_setup.yml`
4. Access: `http://<ec2-public-ip>`

## Files
- `playbooks/httpd_setup.yml`: Ansible playbook.
- `files/index.html`: Webpage.

##sample screenshot for successfull completion
 ![image](https://github.com/user-attachments/assets/ed47211b-1390-434c-9698-91db99e2409c)


## Contact
Rohin Kumili | [https://www.linkedin.com/in/rohin-kumar-kumili-8a636b167]
