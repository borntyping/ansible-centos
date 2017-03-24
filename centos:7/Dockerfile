FROM centos/systemd:latest
RUN yum install -y epel-release
RUN yum install -y python-devel python-pip openssl-devel libffi-devel gcc
RUN pip install --upgrade pip setuptools
RUN pip install ansible testinfra
ADD "inventory.conf" "/etc/ansible/hosts"
