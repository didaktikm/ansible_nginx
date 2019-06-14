[![Build Status](https://travis-ci.org/didaktikm/ansible_nginx.svg?branch=master)](https://travis-ci.org/didaktikm/ansible_nginx)

![Ansible Role](https://img.shields.io/ansible/role/41256.svg) (https://galaxy.ansible.com/didaktikm/ansible_nginx)

## Автоматизация администрирования. Ansible.

Подготовить стенд на Vagrant как минимум с одним сервером. На этом сервере используя Ansible необходимо развернуть nginx со следующими условиями:
- необходимо использовать модуль yum/apt
- конфигурационные файлы должны быть взяты из шаблона jinja2 с перемененными
- после установки nginx должен быть в режиме enabled в systemd
- должен быть использован notify для старта nginx после установки
- сайт должен слушать на нестандартном порту - 8080, для этого использовать переменные в Ansible
* Сделать все это с использованием Ansible роли
