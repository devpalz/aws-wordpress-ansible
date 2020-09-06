# Ansible for Wordpress Deployment onto AWS

## Useful
1. From your local machine you can run `export AWS_PROFILE=personal` and `ansible-inventory -i wordpress-aws_ec2.yml --list` to see the dynamic inventory.
2. Ping all EC2s: `ansible -i wordpress-aws_ec2.yml -m ping`
3. Run playbook `ansible-playbook --inventory wordpress-aws_ec2.yml --become wordpress-playbook.yml`
