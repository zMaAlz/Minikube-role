Minicube-role
=========

Роль для Ansible 2.10 и новее для установки Minicube на Linux. В качестве драйвера для Minikube используется [KVM](https://minikube.sigs.k8s.io/docs/drivers/kvm2/)

Requirements
------------

libvirt v1.3.1 или новее
qemu-kvm v2.0 или новее


Role Variables
--------------

kubectl_version
minicube_version - версия устанавливаемого Minicube

Dependencies
------------

Иные зависимости не требуются. 

Example Playbook
----------------

Пример использования:

---
- name: Install minikube
  hosts: lighthouse
  roles:
    - minikube-role

License
-------

MIT

Author Information
------------------


sminikube start --driver=kvm2

