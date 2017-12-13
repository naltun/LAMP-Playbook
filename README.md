# LAMP playbook for Ansible

This is my adaptation of pix-art's LAMP stack deployment Ansible playbook. This playbook will install PHP 7 and MariaDB 10, configure everything for you, and even create a demo database with a table.

In order to run this playbook, simply run `ansible-playbook -i hosts playbook.yml --become`.

* `-i` is for specifying an `inventory` or `hosts` file
* `--become` is used for _becoming_ root on the host VM before running the tasks, eg `apt install php7.0`

As already mentioned, this is a fork of [pix-art's](https://github.com/pix-art/LAMP-Playbook) LAMP stack deployment Ansible project. pix-art's project came with _no_ license; as such, this fork is being licensed under the GNU GPLv2. To find out more on what that means, please read the attached LICENSE file.
 
