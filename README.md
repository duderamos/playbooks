# My Ansible Playbooks

This is my Ansible Playbooks. 

# Role imap

This role describes a Dovecot director proxy.

Define **hosts** like this:

> [imap]
>
> 172.16.34.93 hostname="imap1.example.com"
>
=======
> 172.16.34.93 hostname="imap1.example.com"
>
> 172.16.34.94 hostname="imap2.example.com"

Alter the **role/imap/vars/main.yml** as you need before running.
