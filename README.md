ansible-role-mysql
=========

install mysql 5.6 on centos6.6

Role Variables
--------------

    mysql_major_version: '5.6'
    mysql_minor_version: '25'
    mysql_version: '{{ mysql_major_version }}.{{ mysql_minor_version }}'
    mysql_src_dir: /usr/local/src
    mysql_prefix_dir: /usr/local/mysql
    mysql_data_dir: /var/lib/mysql
    mysql_root_password: mysql
