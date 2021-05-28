# CleoFunctionalTest
 Automation Functionality Test for SRE position at Cleo

## Pre-Reqs

- Python 2.7+
- Ansible xx
- Botocore/Boto/Boto3
- AWS CLI & 'aws configure' with values from AWS
- AWS Keypair generation

## Vaulted Variables Require key to run

## Keys Removed for Privacy

## Examples

To Create AWS Instance and Dynamic Inventory:
    `ansible-playbook create-ec2.yml -i inventory`

To Configure NGINX Webserver, MySQL Container in Docker, and Wordpress
    `ansible-playbook configure-ec2.yml -i inventory`