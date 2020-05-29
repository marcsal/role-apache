Role Apache
=========

Instalación de servidor apache con plantilla de ejemplo

Requirements
------------

Distro based on Debian

Role Variables
--------------

document_root: "Directorio donde se almacenan los datos de la web"
server_admin: "Email webmaster"
sites_enabled: "Directorio donde se almacenan los ficheros de configuración de la web"
site_name: "Nombre del sitio"

Dependencies
------------

marcsal.role_base

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      remote_user: username
      become: true
      become_user: root
      become_method: sudo
      roles:
        - { role: role-apache }

Author Information
------------------
Marcos Salcedo