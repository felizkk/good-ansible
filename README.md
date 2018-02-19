# good-ansible

repo file secret key = repofile

ansible-playbook site.yml
ansible-playbook site.yml --limit 'apps'
ansible-playbook.site.yml --vault-password-file=vault_pass.txt -- limit 'frontends'
ansible-playbook.site.yml --vault-password-file=vault_pass.txt -- limit 'frontends' -- tags 'index-file,webservice,database'
