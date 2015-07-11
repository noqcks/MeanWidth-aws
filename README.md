# MeanWidth-aws
An ansible playbook for the MeanWidth project

## Quick Start
1.Load ssh key into your keyring via 
```
ssh-add /path/to/ssh/key
```
2.Place the IP of your server in the hosts directory under application
```
[application]
< IP HERE >
``` 
3. Run the playbook
```
ansible-playbook mean-width.yml -i hosts/mean-width -u ubuntu
```