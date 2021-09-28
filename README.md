# ansible_example
ec2でサクっと環境しあげる用

## provisioning environment
```
ansible-playbook -i inventory/local.yml site.yml
```

## deploying app
```
ansible-playbook -i inventory/local.yml deploy.yml
```
