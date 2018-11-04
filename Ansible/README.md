# Ansible

## execute main playbook
`ansible-playbook playbook.yml`

## execute a role via Ad-Hoc
`ansible all -m include_role -a name=example.ping -b`

## generate a role
`(cd roles && ansible-galaxy init __role_name__)`

