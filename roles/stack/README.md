Role Name
=========

This role is primarly used for installing rvm and wkhtmltopdf.  It also adds user environment for building gem packages without doc and ri.

Requirements
------------
This requires generating a password for the user with:

ansible all -i localhost, -m debug -a "msg={{ 'mypassword' | password_hash('sha512', 'mysecretsalt') }}"

https://docs.ansible.com/ansible/latest/reference_appendices/faq.html#how-do-i-generate-encrypted-passwords-for-the-user-module

