ansible-lamp-server
===================

example code used in:

[Installing a LAMP server with Ansible playbooks and roles](http://labs.qandidate.com/blog/2013/11/21/installing-a-lamp-server-with-ansible-playbooks-and-roles/)

[Setting up XHProf/XHGui profiling with Ansible](http://labs.qandidate.com/blog/2013/11/28/setting_up_xhprof_xhgui_profiling_with_ansible/)


-- host
-- playbook.yml
-- roles
   ----- database
         -------- files
                  ---- db.php
                  ---- dump.slq
                  tasks
                  ---- main.yml
          webserver
          -------- files
                   ----- index.php
                   tasks
                   ----- main.yml
-- Vagrantfile
