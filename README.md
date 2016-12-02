##VPS-ANSIBLE

Push your ssh-key on the server in first time.

Use mkpasswd --method=sha-512 to create a password 

Use initial playbook first to created your personnal user.

sudo ansible-playbook playbook.initial.yml

Use second playbook to use your user with sudo like this command :

sudo ansible-playbook myplaybook.yml --ask-sudo-pass
