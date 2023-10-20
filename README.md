---
- name: ping.yml
  hosts: servers
  remote_user: root
  become: yes

  tasks:
   - name: test connection
     ping:
