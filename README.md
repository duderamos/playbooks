# My Ansible Playbooks

This is my Ansible Playbooks. 

# Role imap

This role describes a Dovecot director proxy.

Unfortunately this configuration is not SELinux aware.

Define **hosts** like this:

> [imap]
>
> 172.16.34.93 hostname="imap1.example.com"
>
> 172.16.34.94 hostname="imap2.example.com"

Alter the **role/imap/vars/main.yml** as you need before running.

## Role mbox

This role describes a Dovecot mailbox server.

Unfortunately this configuration is not SELinux aware.

Define **hosts** like this:

> [mbox]
>
> 172.16.34.95 hostname="mbox1.example.com"
>
> 172.16.34.96 hostname="mbox2.example.com"

Alter the **role/mbox/vars/main.yml** as you need before running.
